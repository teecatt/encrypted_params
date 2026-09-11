# encrypted_params

Argon2id 参数（公开、不可变）。

- kdf: argon2id
- mem: 512 MiB
- time: 4
- parallelism: 1
- salt: 固定盐，公开
- cipher: AES-CTR (256-bit key, 随机 IV)

`params.json` 供加密笔记前端读取。本仓库设为 public archive，内容只读。
