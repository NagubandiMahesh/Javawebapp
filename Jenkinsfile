@Library(['devops-dsl@demo']) _
Pipeline
{
    applicationName      = 'new-application'
    mvnGoals             = 'clean package -DskipTests'
    reportDir            = 'target/jacoco-ut/'
    reportFiles          = 'index.html'
    reportName           = 'TestCase HTML Reports'
    buildNode            = 'slave1'
    sonarProjectName     = 'java-sonar-poc'
    sonarProjectKey      = 'java-sonar-poc'
    sonarProjectVersion  = '1.0'
    sonarProjectLanguage = 'java'
    sonarSources         = 'src'
    executeSonar         = 'YES'
    emailRecipientsList  = 'vinay.kumarm@bt.com,swaroopsagar.gaduputi@bt.com'
    deploymentRepo_name       = 'teg'
    ansiblePlaybookfileName   = 'devDeployment.yml'
    ansibleInventory_FileName = 'devInventory.yml'
    deploymentRepo_Path       = '612848076/teg.git'
    application_Name          = 'SimpleWebApplication'
}
