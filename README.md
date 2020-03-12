![face](https://user-images.githubusercontent.com/37928802/76507908-86e97c80-6488-11ea-954b-b9e402b72615.png)

Introduction:
FaceEngine SDK provides the universal interfaces to detect the face information of face, like face detection, age estimation, gender estimation,face angle detection,face liveness detection,ir face liveness detection,face recognition.

Publish date:
06/05/2019

Expire date：（only valid on rgb&ir liveness detection)
07/31/2020

Version:
2.2.12021020101.1

Supported platform:
Android armeabi_v7a

Compile Options:
default

Dependency:
None

Known issues:
None.

File List:
|   |---ArcFaceAPI-Android.zip	JavaDoc
|---libs
|   |---armeabi-v7a
|   |   |---libarcsoft_face.so                	Library
|   |   |---libarcsoft_face_engine.so           	Library
|   |--arcsoft_face.jar			Library
|---samplecode
|   |---ArcfaceDemo


Change Logs:
2018.10.15 
合并多个SDK，集成为单个

2019.01.19 
优化算法，修复bug

2019.03.06 
更新FD和活体模型，支持Android 4.4

2019.06.03
1.更新RGB活体算法库;
2.添加IR活体检测；
3.更新人脸检测算法库；
4.IMAGE模式下仅支持传入单一角度，不再支持全角度检测；
5.IMAGE模式下scale开放的范围为[2,32]，推荐值为30；
6.VIDEO模式下scale开放的范围从[2,16]修改为[2,32]，推荐值为16；
7.VIDEO模式下开放FaceId参数，用于追踪是否为同一张人脸，IMAGE模式下未开放；

