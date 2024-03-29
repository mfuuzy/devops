# 启动 CKB 节点
介绍 CKB 的快速启动, 目前大概需要50G(node+indexer 的数据)的磁盘空间(2024年03月29日)，服务器配置用 4c8g 就够用了。
## docker compose 的启动方法
```
# 主网
docker compose -f docker-compose-ckb-mainnet.yaml  
# 测试网
docker compose -f docker-compose-ckb-testnet.yaml 
```

## k8s 启动节点

```
# 启动
kubectl apply -f deploy-k8s-ckb.yaml
```