keypoints = datum.poseKeypoints  # 관절 좌표
if keypoints is not None:
    wrist = keypoints[0][4]  # 오른쪽 손목 좌표
    print(f"Wrist position: {wrist}")
    
