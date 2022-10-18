# 安装说明  
代码比较久远，建议使用conda环境。  
1）删除pipenv文件。  
2）pip install opencv-python   安装cv2  
3）pip install pillow  安装PIL   

功能说明：Web窗口分为左右两部分，调用摄像头，视频流的实时处理。   


# NodeJS + Python = :sparkles: 

An experimental web app that utilizes both NodeJS and Python to get the best of both worlds.

## Getting started

### Prerequisites

You should have installed on your machine:
- Git (check with `git --version`)
- Python 3 (check with `python3 --version`)
- pipenv (check with `pipenv --version`)
- Node.js (check with `node -v`)
- npm (check with `npm -v`)

Then clone this repository into your workspace.

### Install required packages

Install all required Python packages (given in `Pipfile`) with
```
pipenv install
```
and analogously all required Node packages (given in `package.json`) with
```
npm install
```

### Run the app

Start the Python Flask server with
```
flask run
```
Then, start the NodeJS Express server with
```
node server.js
```
Finally, go to http://localhost:3000 to see the web app.
