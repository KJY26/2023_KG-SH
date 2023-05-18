import math

def calculate_horizontal_distance(angle, initial_velocity, time):
    # 각도를 라디안으로 변환
    angle_rad = math.radians(angle)
    
    # 수평 속도 계산
    horizontal_velocity = initial_velocity * math.cos(angle_rad)
    
    # 수평 거리 계산
    horizontal_distance = horizontal_velocity * time
    
    return horizontal_distance

# 사용자 입력 받기
angle = float(input("각도 (도): "))
initial_velocity = float(input("초기 속도 (미터/초): "))
time = float(input("시간 (초): "))

# 수평 거리 계산
horizontal_distance = calculate_horizontal_distance(angle, initial_velocity, time)

# 결과 출력
print("수평 거리:", horizontal_distance, "미터")
