

node {
stage ('Build'){
 def outfile = "/tmp/output.log"
 
checkout scm > /dev/null 2>&1
}
 stage ('try') {
  
def userInput = input(
 id: 'userInput', message: 'Let\'s promote?', parameters: [
 [$class: 'TextParameterDefinition', defaultValue: 'uat', description: 'Environment', name: 'env']
])
echo ("Env: "+userInput)
}
stage ('Test'){
echo 'nothing to add'
}
stage ('Deploy'){
echo 'Nothing to add'
}
}
