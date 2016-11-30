---
layout: news_post
title: "Ra mắt phiên bản Ruby 2.0.0-p598"
author: "usa"
translator: "Victor Tran"
date: 2014-11-13 12:00:00 +0000
lang: vi
---

Chúng tôi rất vui mừng ra mắt phiên bản Ruby 2.0.0-p598.

Phiên bản này bao gồm bản vá lỗ hổng bảo mật từ chối dịch vụ REXML.
Tương tự như
[lỗ hổng đã được vá](https://www.ruby-lang.org/vi/news/2014/10/27/rexml-dos-cve-2014-8080/)
trong [phiên bản trước](https://www.ruby-lang.org/vi/news/2014/10/27/ruby-2-0-0-p594-is-released/),
nhưng phiên bản này giải quyết vấn đề thực thể giãn nở.
Các bạn có thể xem thêm chi tiết ở chủ đề bên dưới.

* [CVE-2014-8090: Tấn công từ chối dịch vụ giãn nở XML khác](https://www.ruby-lang.org/vi/news/2014/11/13/rexml-dos-cve-2014-8090/)

Một số lỗi khác cũng đã được sửa.
Xem thêm chi tiết trong [tickets](https://bugs.ruby-lang.org/projects/ruby-200/issues?set_filter=1&amp;status_id=5)
và [ChangeLog](http://svn.ruby-lang.org/repos/ruby/tags/v2_0_0_598/ChangeLog).

## Tải về

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.bz2](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.bz2)

      SIZE:   10758882 bytes
      MD5:    a3f3908103a7d209d1d1cf4712e3953c
      SHA256: 67b2a93690f53e12b635ba1bcdbd41e8c5593f13d575fea92fdd8801ca088f0f
      SHA512: 10026a04e01a8ad14ea9c99bbdf4f7d04029b73ee0c01bbf6c2eb2817332d49adacf127b646693b67b5dd7010eaf3b696b23b6335cc0f7ee5a6b56dbba0f6f82

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.gz](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.gz)

      SIZE:   13608640 bytes
      MD5:    e043a21ce0d138fd408518a80aa31bba
      SHA256: 4136bf7d764cbcc1c7da2824ed2826c3550f2b62af673c79ddbf9049b12095fd
      SHA512: 0548aba9bf45e380e5f73e73168ea7fea341fc9739e108c7d530d11b677f6a78b2c4e29062d16a73b4286acaa2333ed20cb34e16b65b5b6898da66661f1717da

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.xz](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.tar.xz)

      SIZE:   8316092 bytes
      MD5:    2ec36f7018eef05003bf8cf0e0f05def
      SHA256: 9dccf4c30e1bb004b18cb1129d9daac3c0ec510a671f4f4f13a2747897ffab35
      SHA512: bf7b93d9fbaab98a64d1f45c3f3bbcdfebd3e1d0584dfb27696b2716d93c2ba13881e1edaef6d3eccd769ac2e21d6157024c902f3d891951a20b972c1942ef99

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.zip](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p598.zip)

      SIZE:   15126384 bytes
      MD5:    aa6ac22747947e6562d5b0dc9767ecda
      SHA256: d5bdafd7b0fbd4254902ba10385c6e5812beac4ad221805aa4d92a37eff47f97
      SHA512: 6cdaf7f2d27a5f0ead9b94325b9c9fe90cf04c64dedaea8e1d45a8855a73ad61c5c72f1fda835eab73693c25c15a74c7e4e639ed5c18a9433dd79e398600b3ea

## Ý kiến cho phiên bản này

Xin lỗi nếu sự ra mắt các phiên bản một cách thường xuyên gây ra bất tiện cho các bạn.
Cảm ơn tất cả mọi người đã đóng góp công sức để ra mắt phiên bản này.
