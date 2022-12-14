# Desplegando infraestructura en la nube con código

> Charla en Calzada Code

# Tabla de Contenido

1. [Demo](#demo)
2. [Enlaces](#enlaces)

![](img/DALL%C2%B7E%202022-12-13%2019.55.45%20-%20A%203D%20render%20of%20a%20lion%20wearing%20glasses%20and%20headphones%20in%20an%20office%20programming%20on%20his%20laptop.png)

# Demo

El código para crear la cuenta de almacenamiento en Azure mediante Terraform se encuentra dentro del folder src.

Para ejecutarlo deberás contar con una suscripción de Azure, si no tienes una te dejo el enlace en los requisitos.

## Requisitos
- [Suscripción de Azure](https://azure.microsoft.com/es-mx/free/search/?wt.mc_id=studentamb_118941)

## Procedimiento

1. Ingresa al [Portal de Azure](https://portal.azure.com/) y accede a Cloud Shell.

2. Verifica que terraform esté instalado escribiendo

```
terraform
```

3. Clona el repositorio

```sh
git clone https://github.com/OscarSantos98/calzada-code-workshop.git && cd calzada-code-workshop
```

4. Accede al folder src
```
cd src
```

Si lo deseas puedes cambiar el nombre del grupo de recursos, nombre de la cuenta de almacenamiento, añadir más recursos, etc.

5. Inicializa Terraform
```
terraform init
```

6. Valida
```
terraform validate
```

7. Checa el plan
```
terraform plan
```

8. Despliega la infraestructura
```
terraform apply
```
Ahora confirma con "yes"

9. Destruye la infraestructura
```
terraform destroy
```
Ahora confirma con "yes"

# Enlaces

### API

* [Azure](https://learn.microsoft.com/en-us/rest/api/azure/?wt.mc_id=studentamb_118941)
* [AWS](https://docs.aws.amazon.com/general/latest/gr/aws-apis.html)
* [GCP](https://cloud.google.com/apis/docs/overview)

### SDK
* [Azure](https://azure.microsoft.com/en-us/downloads/?wt.mc_id=studentamb_118941)
* [AWS](https://aws.amazon.com/es/developer/tools/)
* [GCP](https://cloud.google.com/sdk/)

### Resource manager
* [Azure Resource Manager (ARM)](https://learn.microsoft.com/en-us/samples/browse/?expanded=azure&products=azure-resource-manager&wt.mc_id=studentamb_118941)
* [AWS CloudFormation](https://aws.amazon.com/es/cloudformation/)
* [GCP Deployment Manager](https://cloud.google.com/deployment-manager/docs/)

### Templates & IaC
* [ARM Templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview?wt.mc_id=studentamb_118941)
* [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep&wt.mc_id=studentamb_118941)

### Terraform
* [Terraform Registry](https://registry.terraform.io/browse/providers)
* [HashiCorp Configuration Language (HCL)](https://github.com/hashicorp/hcl)
* [Terraform Cheat sheet](https://spacelift.io/blog/terraform-commands-cheat-sheet)

### Tutoriales
* [ARM Templates](https://learn.microsoft.com/en-us/training/modules/create-azure-resource-manager-template-vs-code/?wt.mc_id=studentamb_118941)
* [Terraform Azure](https://developer.hashicorp.com/terraform/tutorials/azure-get-started)
* [Terraform AWS](https://developer.hashicorp.com/terraform/tutorials/aws-get-started)
* [Terraform GCP](https://developer.hashicorp.com/terraform/tutorials/gcp-get-started)

### Ejemplos

#### Terraform
* [terraform-azure-examples](https://github.com/alfonsof/terraform-azure-examples)
* [terraform-aws-examples](https://github.com/alfonsof/terraform-aws-examples)
* [terraform-google-cloud-examples](https://github.com/alfonsof/terraform-google-cloud-examples)
#### SDK
* [azure-python-examples](https://github.com/alfonsof/azure-python-examples)
* [aws-python-examples](https://github.com/alfonsof/aws-python-examples)
* [google-cloud-python-examples](https://github.com/alfonsof/google-cloud-python-examples)
* [azure-java-examples](https://github.com/alfonsof/azure-java-examples)
* [aws-java-v2-examples](https://github.com/alfonsof/aws-java-v2-examples)
* [google-cloud-java-examples](https://github.com/alfonsof/google-cloud-java-examples)