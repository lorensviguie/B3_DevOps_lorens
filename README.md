# B3_DevOps_lorens

[Download🛬](#1-dl-the-repo)  
[Build👷🏻](#2-construct-the-project)  
[Run👟](#3-run-the-project-and-config-the-env)  
[Test🔧](#4-test-the-project)  

## Description TP1

### 1. DL the repo
```bash
git clone git@github.com:lorensviguie/B3_DevOps_lorens.git
```
### 2. Construct the project
```bash
cargo build --release
```
### 3. Run the project and config the env
```bash
export "PING_LISTEN_PORT=8001" && ./target/release/TP1
```
### 4. Test the project
```bash
curl http://localhost:8080/ping
```