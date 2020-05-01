---
layout: post
title:  "PHP Change Allowed Memory Size"
description: How to change allowed memory size in PHP?
tags: php memory
---

If you have this error

```
Fatal error: Allowed memory size of 134217728 bytes exhausted 
(tried to allocate 20480 bytes)
```
or 

To change allowed memory size in PHP, use this code

~~~php
ini_set('memory_limit', '256M'); // 256 MB allocated
~~~




