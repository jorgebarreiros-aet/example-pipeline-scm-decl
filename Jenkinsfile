pipeline{
  agent any
  triggers{
  pollSCM('*/2 * * * *')
  }
  stages{
    stage("Stage1"){
    echo "I LIVE!"
    }
  }
}
