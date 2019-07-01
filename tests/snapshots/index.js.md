# Snapshot report for `tests/index.js`

The actual snapshot is saved in `index.js.snap`.

Generated by [AVA](https://ava.li).

## fail: dont use compression

> Snapshot 1

    'FAIL  file-4.js: 437B > maxSize 300B (no compression)'

## fail: single file larger than limit

> Snapshot 1

    'FAIL  file-2.js: 270B > maxSize 250B (gzip)'

## pass: custom config file

> Snapshot 1

    'PASS  file-5.js: 269B < maxSize 300B (gzip)'

## pass: single file smaller than limit

> Snapshot 1

    'PASS  file-1.js: 270B < maxSize 300B (gzip)'

## pass: use brotli

> Snapshot 1

    'PASS  file-3.js: 240B < maxSize 250B (brotli)'