# Terminology Policy

이 노트에서는 딥러닝 학습과 코드·논문에서 자주 쓰이는 표현을 억지로 번역하지 않는다.

## English-first terms

| 표현 | 메모 |
|---|---|
| forward pass / backward pass | 순전파·역전파보다 실제 사용 표현을 우선 |
| loss / objective | 학습 목적을 나타내는 값 |
| gradient | parameter를 어느 방향으로 바꿀지 나타내는 값 |
| weight / bias | layer parameter |
| parameter / hyperparameter | 학습되는 값 / 사용자가 정하는 값 |
| batch / mini-batch | 한 번에 처리하는 sample 묶음 |
| learning rate | update 크기 |
| optimizer | parameter update 규칙 |
| activation function | non-linearity를 추가하는 함수 |
| embedding | discrete token 등을 vector로 표현한 것 |
| attention / self-attention | 입력 요소 간 중요도를 계산하는 mechanism |
| query / key / value | attention 계산의 세 입력 |
| feature / representation | 입력에서 추출된 표현 |
| training / validation / test | dataset split 및 단계 |
| inference | 학습된 model을 사용해 예측하는 단계 |
| overfitting / underfitting | 학습 데이터 과적합 / 모델 용량 부족 |

처음 등장할 때만 필요하면 짧은 한국어 설명을 덧붙이고, 이후에는 영어 표현을 그대로 사용한다.
