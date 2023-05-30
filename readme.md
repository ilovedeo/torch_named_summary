기존 torchsummary 라이브러리를 수정한 라이브러리입니다.

torchsummary의 경우 pytorch model의 각 module의 이름을 보여주지 않는다는 한계가 있었는데, 이름을 보이도록 수정했습니다.
"get_features"의 경우, 각 layer의 이름 및 input, output과 layer을 저장하고, 이를 ordered dict 형식으로 return하는 기능을 가지고 있습니다.
