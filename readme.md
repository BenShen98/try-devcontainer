File structure

service: docker based service like database
  * docker file to build the service
  * optinal .devcontainer to develop service's stand-alone feature


product: used by end-user, build on service and product-specific logic
  * filelist for git sparse-checkout
  * docker-compose file, utilise service
  * .devcontainer to develop the prodcut


utility:
  * e.g. script to setup workspace for a product (sparse-checkout)


lib: laugnage specific shared libarary
