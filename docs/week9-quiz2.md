# Quiz 2 Study Guide

## Rules

This quiz is closed book and no notes of any kind are permitted.

## Topics

1. What are Open Collector and Tri-State devices
    - Standard TTL: cannot connect two outputs together
    - Open collector
    - Tri-State
1. Minimization
    - By K-map
        - Implicant: any covering of 1
            - Prime implicant: largest possible covering group of 2^m 1s
            - Essential prime implicant: at least one 1 only covered by itself
        - Circling either prime implicants or prime implicates generating SOP or POS solutions respectively
        - 5-8 variable k-maps
    - By Quine McCluskey ( with and without don’t cares )
1. Exclusive OR and exclusive NOR functions
    - Identifying such functions from their K-Maps
        - XOR:  even 1s <=> 0, odd 1s <=> 1
        - XNOR: even 1s <=> 1, odd 1s <=> 0
    - Writing the minimal algebraic function from the K-map
    - Variables negation
        - Even number: equivalent, XOR <=> XOR, XNOR <=> XNOR
        - Odd number:  complement, XOR <=> XNOR
1. Hazards
    - Static 1: *__adjacent__* '1's covered by different prime __*implicants*__.
    - Static 0: *__adjacent__* '0's covered by different prime __*implicates*__.
    - Eliminate: add redundant prime implicants __*or*__ prime implicates.
1. Implementing functions with MSI devices
    - Decoders and using them to implement arbitrary Boolean functions
    - Cascading these devices