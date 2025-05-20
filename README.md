# try-github-action-with-azure
## 功能清單

- [x] 使用 GitHub Actions 更新部署於 AKS 的服務
- [x] 設定 Azure 的 Service Principal 並且建立在 github secrect 內
[Login With a Service Principal Secret 設定步驟](https://github.com/Azure/login?tab=readme-ov-file#login-with-a-service-principal-secret)
- [x] 使用 Terraform 建立 AKS
[使用 Terraform 部署 Azure Kubernetes Service (AKS) 叢集](https://learn.microsoft.com/zh-tw/azure/aks/learn/quick-kubernetes-deploy-terraform?pivots=development-environment-azure-cli)
- [ ] 使用 Terraform 建立 ACR
- [ ] 驗證 AKS 與 ACR
[從 Azure Kubernetes Service (AKS) 對 Azure Container Registry (ACR) 進行驗證](https://learn.microsoft.com/zh-tw/azure/aks/cluster-container-registry-integration?tabs=azure-cli)
- [ ] 當觸發 github action 時，建立 image 並且 push 到 ACR
- [ ] AKS 從 ACR 下載指定的 image
- [ ] argocd 可以取代哪段？

