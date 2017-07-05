### Pre-compiled binaries with Parity - fast, light, and robust Ethereum implementation.

--- 
**Build image:**
`docker build -t parity-bin .`

or

**pull image from Docker Hub:**

`docker pull loadaverage/parity-bin`

---

#### Examples:
**Start [Ropsten](https://github.com/ethereum/ropsten) testnet node using [docker-compose](https://docs.docker.com/compose/):**

```bash
git clone https://github.com/loadaverage/parity-bin && \ 
cd parity-bin && \
docker-compose up -d
```
`NOTE: make sure to adjust volumes and RPC API to your needs`
