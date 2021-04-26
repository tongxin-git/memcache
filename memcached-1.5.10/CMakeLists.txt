cmake_minimum_required(VERSION 3.16)
project(memcached_1_5_10 C)

set(CMAKE_C_STANDARD 99)

include_directories(.)

add_executable(memcached_1_5_10
        assoc.c
        assoc.h
        bipbuffer.c
        bipbuffer.h
        cache.c
        cache.h
        config.h
        crawler.c
        crawler.h
        crc32c.c
        crc32c.h
        daemon.c
        extstore.c
        extstore.h
        hash.c
        hash.h
        items.c
        items.h
        itoa_ljust.c
        itoa_ljust.h
        jenkins_hash.c
        jenkins_hash.h
        linux_priv.c
        logger.c
        logger.h
        memcached.c
        memcached.h
        murmur3_hash.c
        murmur3_hash.h
        openbsd_priv.c
        protocol_binary.h
        sasl_defs.c
        sasl_defs.h
        sizes.c
        slab_automove.c
        slab_automove.h
        slab_automove_extstore.c
        slab_automove_extstore.h
        slabs.c
        slabs.h
        solaris_priv.c
        stats.c
        stats.h
        storage.c
        storage.h
        testapp.c
        thread.c
        timedrun.c
        trace.h
        util.c
        util.h)
