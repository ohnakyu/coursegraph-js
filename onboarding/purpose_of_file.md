#각 파일의 목적

    ##subject-chart.html
        subject-chart.html 파일은 mermaid 라이브러리를 사용하여 컴퓨터공학과의 이수체계도를 자동적으로 생성합니다. mermaid를 사용하면 복잡한 이수체계도를 간단한 텍스트 형식으로 정의하고, 이를 시각적으로 쉽게 이해할 수 있는 다이어그램으로 변환할 수 있습니다. 이 파일은 컴퓨터공학과의 이수체계도에 집중하여 시각화합니다.

    ##show.html
        show.html 파일은 타 학과의 데이터를 미리 입력받아 사용자가 학과를 선택할 수 있게 합니다. 이를 통해 다양한 학과의 이수체계도를 하나의 인터페이스에서 관리하고 시각화할 수 있습니다. 이 파일은 여러 학과의 데이터를 처리할 수 있는 기능을 강조하여, 다양한 이수체계도를 생성하고 비교할 수 있습니다.
    
    ##courses.json
        show.html에서 사용하는 파일로 학과 데이터가 입력되있고 그 데이터를 이용해 show.html안에 그래프를 그리는데 사용한다. 각 노드는 학과의 교과 과목이고 edge는 과목을 우선으로 들어야하는걸 나타낸것이다. 