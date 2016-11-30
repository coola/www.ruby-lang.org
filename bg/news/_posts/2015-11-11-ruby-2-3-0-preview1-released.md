---
layout: news_post
title: "Излезе Ruby 2.3.0-preview1"
author: "naruse"
translator: "Georgi Mitrev"
date: 2015-11-11 14:00:00 +0000
lang: bg
---

Радваме се да обявим излизането на Ruby 2.3.0-preview1.

Това е първият предварителен преглед на Ruby 2.3.0, който включва
много новости и подобрения.

Първата голяма новост е добавянето на [Frozen String Literal](
https://bugs.ruby-lang.org/issues/11473). В Ruby 2.1 `"str".freeze`
е оптимизирано да намали броят на алокациите. Ruby 2.3 въвежда
нов 'магически' коментар и опция, чрез които може да се обявят всички
'string literals' във входните файлове.

Другата голяма новост е добавянето на [Safe Navigation Operator](
https://bugs.ruby-lang.org/issues/11537), който позволява
`obj && obj.foo` да бъде заместено от `obj&.foo`. Подобни оператори
вече съществуват в C#, Groovy и Swift. Добавени са също `Array#dig`
и `Hash#dig`.

[did_you_mean gem](https://bugs.ruby-lang.org/issues/11252) e добавен
към ruby-core. Библиотеката показва потенциални кандидати при `NameError`
и `NoMethodError` за по-лесно дебъгване.

Приятно използване на Ruby 2.3.0-preview1!

## Важни промени от 2.2

* TBD

Виж [Новини](https://github.com/ruby/ruby/blob/v2_3_0_preview1/NEWS) и
[Списък с промени](https://github.com/ruby/ruby/blob/v2_3_0_preview1/ChangeLog)
за повече информация.

## Сваляне

* <https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.0-preview1.tar.bz2>

  * SIZE:   14174035 bytes
  * SHA1:   55ad4f04d7a33ab780458ee0999de9f6124217ea
  * SHA256: 42b9c9e1740a5abe2855d11803524370bd95744c8dcb0068572ed5c969ac7f0f
  * SHA512: ae6d46c87f59e1fd3703b76dfc45bfcf208625f95ab9f4559f0b9f7050e8681f1a6e419f5fa06b704c83e56879c3a9ff1337dba443bcfca76fadb49c97d97a93

* <https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.0-preview1.tar.gz>

  * SIZE:   17560800 bytes
  * SHA1:   6249572e5dca27d8c73a0cbf036e24e5d88fe82f
  * SHA256: dc8f9d48392a2bb226df5f4b4fd2074d81af155cdf3f3799139a6e31e012aefe
  * SHA512: 58384ef6e743dde20ea263692dab86ce9d6d22d722ef4c02a84396aa3128ce06d933d9b69078a3cd666d72320a8a6ffdc93296bc0d5338595b2a44c29d4db383

* <https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.0-preview1.tar.xz>

  * SIZE:   11225228 bytes
  * SHA1:   85b4f631efa4b6435b2b41df6ce6c46da294c4d4
  * SHA256: a88e19d9dc001db8f49ca3986a8a4e69980affff876854585725e40de0eedcd8
  * SHA512: 3be0f3ed4de73509b2f6975fe3fbe28bb4d51df87db6e2c0019e8a107edf49be60b2127ba5b18bca91f9f5964b07f1adde3042dac6327017359eeb130760672b

* <https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.0-preview1.zip>

  * SIZE:   19777010 bytes
  * SHA1:   3458666c250dd333ac4b537be25f1913dd311ea1
  * SHA256: 0fc1d4450e9141f541038a4433f8fb49fb929e43c7bf5985685a4fa7b213a811
  * SHA512: f53653cf11d8dce1d627f7db3a15acca29c74c78735406a5d64bbbdc39fac232ef63110eb4d83521bef40c6f3006d55bbeaf54d1ddab1d4b6e5a13cee9247e85

## Коментар

За повече информация и release schedule:

[ReleaseEngineering23](https://bugs.ruby-lang.org/projects/ruby-trunk/wiki/ReleaseEngineering23)
