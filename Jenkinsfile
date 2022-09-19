@Library('ejemplo-shared-library2') _


def params = [:]
echo ' *******mensaje de entrada **** '
params.put("Tecnologia","JavaLuis")

echo ' *******llamando libreria **** '


if (env.BRANCH_NAME.matches("rama(.*)")){
  echo ' *******branch **** ' + env.BRANCH_NAME
  global_params()
}else{
  echo ' *******branch **** ' + env.BRANCH_NAME
  global_params_dos()
}

echo ' *******fin de libreria **** '
