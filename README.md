# Desafio Pipeline CICD Cloud Build + Terraform.

1. Utilize o git https://github.com/digitalinnovationone/terraform-gcp/tree/main/terraform-exemplo2 para configurar a trigger do Cloud Build.

2. Edite o script para trocar o nome da máquina para cloudbbuildterraform.

3. Salve os arquivos do Estado no Google Cloud Storage.

Submeta o print de cada etapa de configuração do Pipeline .

---

Steps:

- Create new Repository (if using local / Source Repositories)
- Follow steps to add code to your repository (or cloud shell)

- Enable Cloud Build API (and set Billing Account)
- Configure trigger
	- Nome
	- Região
	- Push to a branch / main
	- Autodetect
	- Repository
	- Require Aproval Yes/No
