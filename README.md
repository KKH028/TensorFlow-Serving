# TensorFlow Serving

### Tenserflow_Serving의 Inference Model은 ssd_MobileNet_V1입니다

TensorFlow Serving은 TensorFlow 기반의 모델을 배포하고 서빙하는 데 사용되는 고성능, 유연성이 뛰어난 서버 시스템입니다. 이 시스템은 기계 학습 모델을 프로덕션 환경에서 쉽고 효율적으로 사용할 수 있도록 설계되었으며, 특히 다음과 같은 주요 기능을 제공합니다:
<br><br>
1. **성능**: TensorFlow Serving은 C++로 구현되어 있어 매우 빠른 추론 속도를 제공합니다. 또한, 다양한 하드웨어와 네트워크 조건에서도 안정적인 성능을 유지할 수 있도록 최적화되어 있습니다.
<br><br>
2. **모델 버전 관리**: 이 시스템은 여러 버전의 모델을 동시에 관리할 수 있습니다. 이를 통해 새로운 모델 버전을 롤아웃하고 실험하면서도 이전 버전의 모델을 계속 사용할 수 있습니다. 사용자는 요청시 특정 버전의 모델을 지정하여 사용할 수 있습니다.
<br><br>
3. **확장성**: TensorFlow Serving은 자동으로 확장되어 수천 개의 요청을 동시에 처리할 수 있습니다. 또한, 클러스터 환경에서도 효과적으로 작동하여 대규모 배포에 적합합니다.
<br><br>
4. **구성 용이성**: TensorFlow Serving은 REST API 및 gRPC API를 지원하여 다양한 클라이언트 애플리케이션에서 쉽게 모델에 접근할 수 있게 해줍니다. 이는 다양한 프로그래밍 언어와 플랫폼에서 사용될 수 있으며, API를 통해 모델 호출 및 데이터 전송이 용이합니다.
<br><br>
5. **다양한 배포 옵션**: TensorFlow Serving은 Docker 컨테이너, Kubernetes, 클라우드 기반 서비스 등 다양한 환경에서 구동할 수 있습니다. 이를 통해 다양한 인프라에서의 호환성과 유연성을 보장합니다.
<br><br>
TensorFlow Serving은 주로 복잡한 머신 러닝 모델을 실시간으로 서빙하는 데 사용되며, 자동차, 의료, 금융 등 다양한 산업 분야에서 실시간 의사결정 지원에 활용됩니다. 이 시스템을 사용하여 개발자들은 모델을 빠르게 배포하고 업데이트할 수 있으며, 이는 기업이 혁신을 지속하고 경쟁력을 유지하는 데 중요한 역할을 합니다.
