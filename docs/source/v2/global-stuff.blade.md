---
title: Global Cache/Storage/Assets/...
description: Global Cache/Storage/Assets/...
extends: _layouts.documentation_v2
section: content
---

# Global Cache/Storage/Assets/...

## Global Cache {#global-cache}

Use the `GlobalCache` facade, or the `global_cache()` helper.

## Global Storage {#global-storage}

Create a disk and *don't* add it to `tenancy.filesystem.disks`.

## Global Assets {#global-assets}

Use the `global_asset()` helper.

## Global Database {#global-database}

Create a new connection and use it like `DB::connection($connectionName)->table('foo')->where(...)`

## Global Queues/Jobs {#global-queues-jobs}

Coming soon.
