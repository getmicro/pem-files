# pem-files

Helper repo to compute the set of certs to trust.

```
yarn install
cp node_modules/node_extra_ca_certs_mozilla_bundle/ca_bundle/ca_intermediate_root_bundle.pem ./bundle.pem
git commit -am 'update bundle'
```

https://raw.githubusercontent.com/getmicro/pem-files/main/bundle.pem will have the set of certs to trust.
