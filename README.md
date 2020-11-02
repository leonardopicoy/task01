# task01

# Pre requisitos:
- Azure Service Principal
- Terraform

# Configuracion:

Para poder trabajar el shell task01.sh, debera modificar las variables de las credenciales de AZURE, en el archivo variables.tf.

variable "subscription_id" {
  default = ""
}

variable "client_id" {
  default = ""
}

variable "client_secret" {
  default = ""
}

variable "tenant_id" {
  default = ""
}

# Ejecucion

Se utilizan los siguiente parametros:

# Para crear un Cluster de Kubernetes de un solo nodo, con Ingress Controller.
sh task01.sh CREATE

# Para destruir el Cluster de Kubernetes
sh task01.sh DESTROY

# Para ver las declaraciones
sh task01.sh OUTPUT
