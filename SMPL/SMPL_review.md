# SMPL: A Skinned Multi-Person Linear Model 논문에 대한 정리
## code:https://github.com/vchoutas/smplx/tree/master/transfer_model

### 1.Abstact

목표=>사람마다 다른 체형을 고려하여 natural한 pose를 가진 3D human mesh를 생성

모델의 파라미터 &beta;와 &theta;는 rest-pose-template(T<sup>bar</sup>,aka:zero pose), blend-weight(joint과 vertex간 연관성을 나타내는 지표),
pose-dependent-blend-shape(P,aka:pose blendshapes,논문에서는 서예체로 표기),
identity-dependent blend shapes(S,aka:shape blendshapes,논문에서는 서예체로 표기),
regressor-from-vertices-to-joint-location(J,aka:joint regressor matrix,논문에서 서예체로 표기)으로 학습된다.

pose
