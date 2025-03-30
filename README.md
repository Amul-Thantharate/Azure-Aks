# Azure AKS Terraform Configuration 🚀

This repository contains Terraform configurations for deploying and managing Azure Kubernetes Service (AKS) clusters.

## 📋 Prerequisites

- Azure CLI installed and configured
- Terraform (version >= 1.0.0)
- Azure subscription
- Git

## 🛠️ Setup Instructions

1. Clone this repository:
```bash
git clone <repository-url>
cd Azure-Aks
```

2. Initialize Terraform:
```bash
terraform init
```

3. Configure Azure credentials:
```bash
az login
```

## 📝 Configuration

Update the following files according to your requirements:
- `variables.tf` - Define your variable values
- `terraform.tfvars` - Set your specific configuration values

## 🚀 Deployment

1. Review the deployment plan:
```bash
terraform plan
```

2. Apply the configuration:
```bash
terraform apply
```

## 🏗️ Infrastructure Components

- AKS Cluster
- Virtual Network
- Subnets
- Network Security Groups
- Managed Identities
- Azure Container Registry (optional)

## 🔑 Security Features

- RBAC enabled
- Network policies
- Azure AD integration
- Private cluster option

## 🧹 Cleanup

To destroy the infrastructure:
```bash
terraform destroy
```

## 📚 Directory Structure

```
Azure-Aks/
├── main.tf
├── variables.tf
├── outputs.tf
├── providers.tf
└── README.md
```

## 🤝 Contributing

Feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License.

## ⚠️ Important Notes

- Always review the changes before applying
- Keep your credentials secure
- Regularly update your Terraform providers

## 📞 Support

For support, please open an issue in the repository.

---
⭐ Don't forget to star this repo if you find it helpful!
