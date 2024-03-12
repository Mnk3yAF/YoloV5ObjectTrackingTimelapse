# yolov5 object tracking and timelapse

### Based on the open source repository yolov5-object-tracking (https://github.com/RizwanMunawar/yolov5-object-tracking)



### Pre-Requsities
- Python 3.9 (Python 3.7/3.8 can work in some cases)

### Steps to run Code
- Clone the repository
```
git clone https://github.com/RizwanMunawar/yolov5-object-tracking.git
```

- Goto the cloned folder.
```
cd yolov5-object-tracking
```

- Create a virtual envirnoment (Recommended, If you dont want to disturb python packages)
```
python -m venv env
env\Scripts\activate  # For Windows
source env/bin/activate  # For Linux/macOS

```

- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```

- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```

- Run the code with mentioned command below.
```
python -m streamlit run app.py
```

- Output file will be created in the working-dir/runs/detect/exp with original filename


<b>Note:</b> Make sure, to add video in the <b>yolov5-object-tracking</b> folder, that you want to run on streamlit dashboard. Otherwise streamlit server will through an error.

### Known Bugs
- Labels do not attach properly to bounding boxes after some time 
