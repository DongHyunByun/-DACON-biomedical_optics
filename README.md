# -DACON-biomedical_optics

# https://dacon.io/competitions/official/235608/overview/

1. 목적 : 현재 뇌전도 검사를 위해 전극을 머리에 찌르는 방법을 사용한다. 이를 대체하기 위해 빛을 응용하여 뇌내 성분검사를 한다.
2. 데이터
    1. x값
        1. id
        2. rho(측정거리)
        3. src(광원스펙트럼)
        4. dst(측정스펙트럼)
    2. y값
        1. hhb(디옥시헤모글로빈 농도)
        2. hbo2(옥시헤모글로빈 농도)
        3. ca(칼슘농도)
        4. na(나트륨농도)
3. 평가
    1. 측정지표 : Mean Absolute Error(MAE)
    2. 채점 : 대회중엔 20%만 측정, 종료후 최종순위는 나머지 80%까지 합산. 
