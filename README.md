https://github.com/sigstore/cosign

```
-----BEGIN PUBLIC KEY-----
MFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEOkkvPVP8GsIuDb/JlW824Kqe27Dl
VgsKJF6rqNDlhgezQg/Hf/2Qo6Y3fzmMq38C2z8Hzhf2MHiTm84hlhZ7cw==
-----END PUBLIC KEY-----
```

The one commit of this repository is signed using cosign.

Credits to: https://github.com/sigstore/cosign/blob/main/FUN.md


```
./cosign verify-blob -key cosign.pub -signature <(git notes show HEAD) <(git rev-parse HEAD)
```
