pipeline {
  agent any
  stages {
    stage('检11111111111') {
      steps {
        sleep 40
        echo '接口测试中...'
        echo '接口测试完成.'
      }
    }
    stage('测试qq') {
      parallel {
        stage('单元测试q') {
          steps {
            echo 'pwd'
          }
        }
        stage('接口测试wq') {
          steps {
            echo '接口测试中...'
            //sleep 30
            echo '接口测试完成.'
          }
        }
        stage('brancheq') {
          when {
            branch 'test'
          }
          steps {
            //sleep 30
            echo 'run master.......'
            //git 'https://github.com/linzhongli-0419/test_repo1p（此repo不存在）'
          }
        }
      }
    }
    stage('测试qqq') {
      parallel {
        stage('单元测试qq') {
          steps {
            //sleep 30
            echo 'pwd'
          }
        }
        stage('接口测试wqq') {
          steps {
            //sleep 30
            echo '接口测试中...'
            echo '接口测试完成.'
            //git 'https://github.com/linzhongli-0419/test_repo1p（此repo不存在）'
          }
        }
      }
    }
    stage('检出q') {
      steps {
        //sleep 30
        echo '接口测试中...'
        echo '接口测试完成.'
      }
    }
  }
}
