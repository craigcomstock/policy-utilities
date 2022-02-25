# Various Utilities for writing CFEngine policy

A collection of `cfbs` addable utilities to make policy easier to write.

# download

``` cf3
  vars:
    "k3s_url" string => "https://github.com/k3s-io/k3s/releases/download/v1.23.4%2Bk3s1/k3s";
  methods:
    "download_k3s" usebundle => download("${k3s_url}", "/tmp/k3s");
```
