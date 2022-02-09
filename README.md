# terraform
 
## 1 ESXI
- La compatibilité de Terraform avec ESXI ( sans passer par vSphere) a vu le jour grâce aux efforts de [Jonathan Senkerik
](https://github.com/josenk/terraform-provider-esxi)
- Prerecquis :
    - un serveur ESXI disponible + ses identifiants ssh
    - Install terraform : Télécharget et installer  Terraform sur ta machine locale en suivant les instructions suivantes https://www.terraform.io/downloads.html. ( Télécharger le .zip, placer terraform.exe dans %Dossier_installation%\HashiCorp\Terraform , ajouter le à path)
    - edit variables.tf