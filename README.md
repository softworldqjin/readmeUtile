# BiddingGo 

<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/1e36c230-8248-44f6-b5f0-971a78c39e9b" width="300"/>
</p>

<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/e839d356-1bb6-477b-a87f-feeed40d6e67"  width="1200"/>
</p>


# Bidding mate

<table>
  
  <tr>
    <th>김진혁</th>
    <th>박선우</th>
    <th>윤정윤</th>
    <th>이민경</th>
    <th>이애은</th>
    <th>한규진
  </tr>
  
  <tr>
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="김진혁" src="https://github.com/user-attachments/assets/d44abc12-4269-4be2-a6a9-f76a531a963f" /></td>
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="박선우" src="https://github.com/user-attachments/assets/cf47d2b7-7633-4f17-8cbe-8b6429ceef67" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="윤정윤" src="https://github.com/user-attachments/assets/5cde1533-77e1-4783-8ce9-d48ec236c25d" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="이민경" src="https://github.com/user-attachments/assets/f62ebf05-846f-462e-b4d3-3fa3c58ce4fb" /></td>  
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="이애은" src="https://github.com/user-attachments/assets/79be4278-e3e9-44c5-af71-57d1831e9406" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="한규진" src="https://github.com/user-attachments/assets/45b114ef-0e30-4bcc-94d2-dfd548aa9b7c" /></td>  
  </tr>

  <tr>
    <td align="center">
      <a href="https://github.com/jin605"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td> 
    <td align="center">
      <a href="https://github.com/melly8954"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/penep0"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/alskung1101"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/nueeaeel"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/softworldqjin"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
  </tr>
</table>
    
---


# 목차
<br/>

1. [프로젝트 개요](#1--프로젝트-개요)
2. [시스템 아키텍처](#2--시스템-아키텍처)
3. [CICD 파이프라인](#3--CICD-파이프라인)
4. [시현](#4--시현)
5. [회고](#5--회고)

<br/>

---


# 1.  프로젝트 개요
<br/> 

## 📍 프로젝트 소개
**Biddinggo는 실시간 경매 기반의 중고 및 리셀 거래 플랫폼입니다.**  
사용자는 상품을 등록하고 다양한 경매 방식(일반 경매, 연장 경매, 타임딜 등)을 통해 판매할 수 있으며, 구매자는 실시간 입찰을 통해 원하는 상품을 경쟁적으로 구매할 수 있습니다.  

또한, 실시간 알림(SSE) 기반으로 입찰 상황을 즉시 반영하여 사용자에게 몰입감 있는 거래 경험을 제공합니다.  
특히, **빅크리 경매(Vickrey Auction, 2등 가격 경매)** 방식을 도입하여 보다 공정하고 전략적인 가격 형성을 지원합니다.

---

## 📍 배경 (이 서비스가 필요한 이유)

### 1. 기존 중고 거래 플랫폼의 가격 결정 한계
- 번개장터, 당근마켓 등은 정가 기반 거래로 적정 가격 형성이 어려움  
- 협상 과정이 비효율적이며 사용자 경험 저하  

### 2. 리셀 시장 성장과 공정한 거래 필요성 증가
- 한정판 및 인기 상품은 가격 변동성이 큼  
- 경매 방식이 가장 합리적인 가격 형성 구조지만 지원 플랫폼이 제한적  

### 3. 기존 경매 플랫폼의 UX 및 기능 한계
- UI/UX가 직관적이지 않고 사용성이 떨어짐  
- 실시간 입찰 경험 부족 및 시스템 반응 속도 문제  

---

## 📍 기존 서비스와의 차별점

### 📌 기존 서비스

#### KREAM
- 패션/스니커즈 특화 플랫폼  
- 모든 거래에 검수 필수 → 거래 속도 느림  
- 경매 방식이 아닌 호가 기반 거래  

#### 코베이옥션
- 전통적인 경매 플랫폼  
- UI/UX가 올드하고 접근성이 낮음  
- 실시간성 및 사용자 경험 부족  

---

### ✅ Biddinggo의 차별점

#### 1. 빅크리(Vickrey) 기반 경매 시스템
- 최고 입찰자가 낙찰되지만, 실제 결제 금액은 두 번째로 높은 입찰가로 결정  
- 과도한 가격 경쟁 방지  
- 사용자가 자신의 최대 지불 의사를 정직하게 반영하도록 유도  

#### 2. AI 기반 상품 예측가 제공
- 과거 거래 데이터 및 유사 상품 데이터를 기반으로 적정 가격 제시  
- 판매자/구매자 모두 합리적인 의사결정 가능  

#### 3. AI 기반 유사 상품 검색
- 이미지 및 텍스트 기반 유사도 분석  
- 검색 효율 및 사용자 경험 향상  

#### 4. 다양한 경매 옵션 제공
- 연장 경매 (마감 직전 입찰 시 자동 연장)  
- 타임딜 경매 (짧은 시간 집중 경쟁)  
- 검수 경매 (신뢰 기반 거래)  

#### 5. 실시간 입찰 시스템 (SSE 기반)
- 입찰 상태 및 알림을 실시간 반영  
- 사용자 간 경쟁 상황을 즉각적으로 체감 가능  

#### 6. 100% 에스크로 기반 안전 거래
- 거래 금액을 중간 보관 후 완료 시 정산  
- 구매자/판매자 자산 보호  

#### 7. 현대적인 UI/UX
- 직관적인 경매 흐름 제공  
- 기존 경매 서비스 대비 사용성 개선  

---

## 📍 기대 효과

- **합리적인 가격 형성**
  - 빅크리 경매 구조를 통한 공정한 시장 가격 결정  

- **거래 신뢰도 향상**
  - 에스크로 + 검수 옵션 기반 안전 거래 환경  

- **사용자 참여도 증가**
  - 실시간 입찰 및 알림으로 몰입도 상승  

- **판매 효율 극대화**
  - 다양한 경매 옵션을 통한 유연한 판매 전략  

- **플랫폼 경쟁력 확보**
  - AI + 실시간 시스템 + 경매 구조 결합
<br/>

---

# 2.  시스템 아키텍처
<br/>
<img width="1235" height="1134" alt="Image" src="https://github.com/user-attachments/assets/96d61b52-ec98-406d-bae5-0f93b300c47b" />

<br/>

---

# 3.  CICD 파이프라인
<br/>

<details><summary>통합 관리 Jenkins 파이프라인</summary>
<br/>
<img width="1123" height="446" alt="Image" src="https://github.com/user-attachments/assets/6bb90a71-f81b-4b24-b9d6-31646931829a" />
<br/>
  
```
pipeline {
  agent any

  environment {
    FRONTEND_JOB = 'biddinggo-frontend'
    BACKEND_JOB = 'biddinggo-backend'
  }

  stages {
    stage('Check CI Skip') {
      steps {
        script {
          def skipStatus = sh(script: 'git rev-parse --is-inside-work-tree >/dev/null 2>&1 && git log -1 --pretty=%B | grep -q "\\[skip ci\\]"', returnStatus: true)
          env.SKIP_PIPELINE = skipStatus == 0 ? 'true' : 'false'
          if (env.SKIP_PIPELINE == 'true') {
              env.SKIP_REASON = 'latest commit contains [skip ci]'
              echo 'Skipping build because the latest commit contains [skip ci].'
          }
        }
      }
    }

    stage('Detect Changed Areas') {
      when {
        expression { env.SKIP_PIPELINE != 'true' }
      }
      steps {
        script {
          def baseCommit = env.GIT_PREVIOUS_SUCCESSFUL_COMMIT ?: env.GIT_PREVIOUS_COMMIT
          def changedText = ''

          if (baseCommit?.trim() && sh(script: "git cat-file -e ${baseCommit}^{commit}", returnStatus: true) == 0) {
            changedText = sh(script: "git diff --name-only ${baseCommit} HEAD", returnStdout: true).trim()
          } else {
            changedText = sh(script: "git show --name-only --pretty=format:'' HEAD", returnStdout: true).trim()
          }

          def changedFiles = changedText ? changedText.split('\n').findAll { it } : []

          env.FRONTEND_CHANGED = changedFiles.any { it.startsWith('infra/k8s/frontend/') }.toString()
          env.BACKEND_CHANGED = changedFiles.any { it.startsWith('infra/k8s/backend/') }.toString()

          echo "Changed files:\n${changedFiles.join('\n')}"
          echo "Frontend changed: ${env.FRONTEND_CHANGED}"
          echo "Backend changed: ${env.BACKEND_CHANGED}"
        }
      }
    }

    stage('Trigger Build Jobs') {
      when {
        expression { env.SKIP_PIPELINE != 'true' }
      }
      steps {
        script {
          if (env.FRONTEND_CHANGED == 'true') {
            echo "Triggering frontend job: ${env.FRONTEND_JOB}"
            def frontendBuild = build job: env.FRONTEND_JOB, wait: true
            env.FRONTEND_BUILD_NUMBER = frontendBuild.number.toString()
          }

          if (env.BACKEND_CHANGED == 'true') {
            echo "Triggering backend job: ${env.BACKEND_JOB}"
            def backendBuild = build job: env.BACKEND_JOB, wait: true
            env.BACKEND_BUILD_NUMBER = backendBuild.number.toString()
          }

          if (env.FRONTEND_CHANGED != 'true' && env.BACKEND_CHANGED != 'true') {
            echo 'No frontend/backend source changes detected. Nothing to trigger.'
          }
        }
      }
    }
  }

  post {
    success {
      script {
        if (env.SKIP_PIPELINE == 'true') {
          echo """
============================================================
  ⏭️  CI skipped
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  📝 Reason
    Message    : ${env.SKIP_REASON ?: 'latest commit contains [skip ci]'}

============================================================
"""
        } else {
          echo """
============================================================
  ✅ BiddingGo coordinator pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🚦 Trigger
    Frontend   : ${env.FRONTEND_CHANGED == 'true' ? env.FRONTEND_JOB : 'skipped'}
    Backend    : ${env.BACKEND_CHANGED == 'true' ? env.BACKEND_JOB : 'skipped'}

============================================================
"""
        }
      }
    }
    failure {
      echo """
============================================================
  ❌ BiddingGo coordinator pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}

```
</details>

<br/>

<details><summary>프론트엔드 Jenkins 파이프라인</summary>
<br/>
<img width="1127" height="440" alt="Image" src="https://github.com/user-attachments/assets/5c6c32db-d821-44ff-8f2c-358b3284f367" />
<br/>
  
```
pipeline {
  agent any

  options {
    disableConcurrentBuilds()
  }

  environment {
    GHCR_REGISTRY = 'ghcr.io'
    GHCR_OWNER = 'beyond-sw-camp'
    IMAGE_NAME = 'be25-3rd-biddingmate-biddinggo'
    GHCR_IMAGE_NAME = "${GHCR_REGISTRY}/${GHCR_OWNER}/${IMAGE_NAME}"

    CICD_REPO_URL = 'github.com/beyond-sw-camp/be25-4th-biddingmate-biddinggo.git'
    FRONTEND_DEPLOYMENT_MANIFEST = 'infra/k8s/frontend/deployment.yaml'

    VITE_API_BASE_URL = 'https://api.bidding-go.shop'
    VITE_TOSS_CLIENT_KEY = 'test_ck_4yKeq5bgrpPoPA0lxOkXrGX0lzW6'
  }

  stages {
    stage('Docker Build') {
      steps {
        script {
          env.IMAGE_TAG = "${env.BUILD_NUMBER}"
        }

        sh '''
          docker build --no-cache \
            --build-arg VITE_API_BASE_URL=$VITE_API_BASE_URL \
            --build-arg VITE_TOSS_CLIENT_KEY=$VITE_TOSS_CLIENT_KEY \
            -t $GHCR_IMAGE_NAME:$IMAGE_TAG \
            -t $GHCR_IMAGE_NAME:latest \
            .
        '''

        sh 'docker image inspect $GHCR_IMAGE_NAME:$IMAGE_TAG'
      }
    }

    stage('Push to GHCR') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            echo "$GITHUB_TOKEN" | docker login $GHCR_REGISTRY -u "$GITHUB_USER" --password-stdin
            docker push $GHCR_IMAGE_NAME:$IMAGE_TAG
            docker push $GHCR_IMAGE_NAME:latest
            docker logout $GHCR_REGISTRY
          '''
        }
      }
    }

    stage('Update Frontend Deployment') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            rm -rf cicd-repo
            git clone https://$GITHUB_USER:$GITHUB_TOKEN@$CICD_REPO_URL cicd-repo

            cd cicd-repo

            git config user.name "jenkins-bot"
            git config user.email "jenkins-bot@users.noreply.github.com"

            sed -i "s|image: .*|image: $GHCR_IMAGE_NAME:$IMAGE_TAG|" $FRONTEND_DEPLOYMENT_MANIFEST

            grep "image: $GHCR_IMAGE_NAME:$IMAGE_TAG" $FRONTEND_DEPLOYMENT_MANIFEST

            git diff -- $FRONTEND_DEPLOYMENT_MANIFEST
            git add $FRONTEND_DEPLOYMENT_MANIFEST
            git diff --cached --quiet && echo "No frontend image change." || git commit -m "ci: update frontend image to $IMAGE_TAG [skip ci]"
            git pull --rebase origin main
            git push origin main
          '''
        }
      }
    }
  }

  post {
    success {
      echo """
============================================================
  ✅ BiddingGo frontend pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🐳 Image
    Version    : ${env.GHCR_IMAGE_NAME}:${env.IMAGE_TAG}

============================================================
"""
    }

    failure {
      echo """
============================================================
  ❌ BiddingGo frontend pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}
```
</details>

<br/>

<details><summary>백엔드 Jenkins 파이프라인</summary>
<br/>
<img width="1121" height="442" alt="Image" src="https://github.com/user-attachments/assets/7b034184-27c5-470a-9f05-fa271e4390db" />
<br/>
  
```
pipeline {
  agent any

  options {
    disableConcurrentBuilds()
  }

  environment {
    GHCR_REGISTRY = 'ghcr.io'
    GHCR_OWNER = 'beyond-sw-camp'
    IMAGE_NAME = 'be25-2nd-biddingmate-biddinggo'
    GHCR_IMAGE_NAME = "${GHCR_REGISTRY}/${GHCR_OWNER}/${IMAGE_NAME}"

    CICD_REPO_URL = 'github.com/beyond-sw-camp/be25-4th-biddingmate-biddinggo.git'
    BACKEND_DEPLOYMENT_MANIFEST = 'infra/k8s/backend/deployment.yaml'
  }

  stages {
    stage('Docker Build') {
      steps {
        script {
          env.IMAGE_TAG = "${env.BUILD_NUMBER}"
        }

        sh '''
          docker build --no-cache \
            -t $GHCR_IMAGE_NAME:$IMAGE_TAG \
            -t $GHCR_IMAGE_NAME:latest \
            .
        '''

        sh 'docker image inspect $GHCR_IMAGE_NAME:$IMAGE_TAG'
      }
    }

    stage('Push to GHCR') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            echo "$GITHUB_TOKEN" | docker login $GHCR_REGISTRY -u "$GITHUB_USER" --password-stdin
            docker push $GHCR_IMAGE_NAME:$IMAGE_TAG
            docker push $GHCR_IMAGE_NAME:latest
            docker logout $GHCR_REGISTRY
          '''
        }
      }
    }

    stage('Update Backend Deployment') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            rm -rf cicd-repo
            git clone https://$GITHUB_USER:$GITHUB_TOKEN@$CICD_REPO_URL cicd-repo

            cd cicd-repo

            git config user.name "jenkins-bot"
            git config user.email "jenkins-bot@users.noreply.github.com"

            echo "Before:"
            grep -n "image:" $BACKEND_DEPLOYMENT_MANIFEST

            sed -i "s|image: .*|image: $GHCR_IMAGE_NAME:$IMAGE_TAG|" $BACKEND_DEPLOYMENT_MANIFEST

            echo "After:"
            grep -n "$GHCR_IMAGE_NAME:$IMAGE_TAG" $BACKEND_DEPLOYMENT_MANIFEST

            git diff -- $BACKEND_DEPLOYMENT_MANIFEST
            git add $BACKEND_DEPLOYMENT_MANIFEST
            git diff --cached --quiet && echo "No backend image change." || git commit -m "ci: update backend image to $IMAGE_TAG [skip ci]"
            git pull --rebase origin main
            git push origin main
          '''
        }
      }
    }
  }

  post {
    success {
      echo """
============================================================
  ✅ BiddingGo backend pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🐳 Image
    Version    : ${env.GHCR_IMAGE_NAME}:${env.IMAGE_TAG}

============================================================
"""
    }

    failure {
      echo """
============================================================
  ❌ BiddingGo backend pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}
```
</details>

---

# 4.  시현
<br/>

🔗[ 백 ]( )

🔗[ 백 ]( )

🔗[ 백 ]( )

🔗[ 프론트 ]( )

🔗[ 프론트 ]( )

🔗[ 프론트 ]( )

🔗[ 1 ]( )



<br/>

---


# 5.  발표자료
<br/>

🔗[발표자료]( )
<br/>

---

# 11.  회고
<br/>

#### 김진혁
>11 
 
#### 박선우
>11

#### 윤정윤
>11

#### 이민경
>11

#### 이애은
>11

#### 한규진
>11
