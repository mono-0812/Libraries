---
data:
  _extendedDependsOn: []
  _extendedRequiredBy: []
  _extendedVerifiedWith: []
  _isVerificationFailed: false
  _pathExtension: py
  _verificationStatusIcon: ':heavy_check_mark:'
  attributes:
    PROBLEM: https://judge.yosupo.jp/problem/aplusb
    links:
    - https://judge.yosupo.jp/problem/aplusb
  bundledCode: "Traceback (most recent call last):\n  File \"/opt/hostedtoolcache/Python/3.10.1/x64/lib/python3.10/site-packages/onlinejudge_verify/documentation/build.py\"\
    , line 71, in _render_source_code_stat\n    bundled_code = language.bundle(stat.path,\
    \ basedir=basedir, options={'include_paths': [basedir]}).decode()\n  File \"/opt/hostedtoolcache/Python/3.10.1/x64/lib/python3.10/site-packages/onlinejudge_verify/languages/python.py\"\
    , line 96, in bundle\n    raise NotImplementedError\nNotImplementedError\n"
  code: "# verification-helper: PROBLEM https://judge.yosupo.jp/problem/aplusb\ndef\
    \ aplusb(a,b):\n    return a+b\na,b=map(int,input().split()) \n\nprint(aplusb(a,\
    \ b))"
  dependsOn: []
  isVerificationFile: true
  path: aplusb.test.py
  requiredBy: []
  timestamp: '2022-01-18 20:58:45+09:00'
  verificationStatus: TEST_ACCEPTED
  verifiedWith: []
documentation_of: aplusb.test.py
layout: document
redirect_from:
- /verify/aplusb.test.py
- /verify/aplusb.test.py.html
title: aplusb.test.py
---
