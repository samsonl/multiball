node() {
  echo "OK ${env.JOB_NAME}"
  echo "BN ${env.BRANCH_NAME} CB:${env.CHANGE_BRANCH} CH:${env.CHANGE_ID}" 
  checkout scm
  bat "type file1.txt"
}
