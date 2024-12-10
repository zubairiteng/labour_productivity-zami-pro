
# Labour Productivity

The YOLOv8 model is trained to detect the following five classes:

1- Customer\
2- Visitor\
3- Shelf\
4- Counter\
5- Other (excluded from visualization and reporting)




# How to Run
Following is the guide to run and post-process the video:

## Give the relevant Paths
video_path = 'RS.mp4'
model_path = 'runs/detect/train8/weights/best.pt'
output_video_path = 'output_video.mp4'
output_excel_path = 'output_counts.xlsx'

## Call the function
process_video(video_path, model_path, output_video_path, output_excel_path)
