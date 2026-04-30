# CHANGELOG

## [v1.1] - Mejora de documentación

### Añadido
- Se ha ampliado la documentación del proyecto en `README.md`.
- Se ha documentado el flujo de despliegue automático con Terraform y LocalStack.

### Mantenido
- Se conserva el workflow de GitHub Actions para ejecutar `terraform init`, `terraform plan` y `terraform apply`.

---

## [v1.0] - Versión inicial

### Añadido
- Configuración inicial del proyecto Terraform.
- Archivo `main.tf` con proveedor AWS configurado para LocalStack.
- Workflow de validación automática con `terraform validate`.
- Workflow de despliegue automático contra LocalStack.
