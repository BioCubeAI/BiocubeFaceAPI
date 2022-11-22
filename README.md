![Logo](https://www.biocube.ai/assets/img/biocube.svg)


# BioCubeFaceAPI

BiocubeFaceAPISDK offers Face Detection APIs for Mobile applications and extensible resource decoding pipelines and automatic resource pooling. Biocube FaceAPISDK is a fast and efficient image processing and provides a unified embedding for face recognition, verification, and authentication. It maps each face image into a euclidean space such that the distances in that space correspond to face similarity, i.e. an image of person A will be placed closer to all the other images of person A as compared to images of any other person present in the dataset. Face Detection is one of the used and popular frameworks of Machine Learning in many different user applications such as Camera apps, Verification Apps, surveillance, and security apps. But it is often underrated due to the complexity it brings for many researchers and Machine Learning experts. This technology has engraved its path on mobile devices as well where many researchers just focus on the performance of Face Detection results only on small handheld devices. Face Detection works with Detection and Estimation algorithms to get us the approximate results.

## Installation

You can download a jar from GitHub's releases page.

Or use Gradle:

```bash
 repositories {
 	...
maven { url 'https://jitpack.io' }
}
```

   ```bash
   Dependencies{

//User for camera access
def cameraxVersion = "1.3.0-alpha01"
implementation "androidx.camera:camera-view:${cameraxVersion}"
implementation "androidx.camera:camera-camera2:${cameraxVersion}"

//Google Ml Ket
implementation 'com.google.mlkit:face-detection:16.1.5'

	//User for BioCube FaceAPI SDK
implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
implementation 'com.github.BioCubeAI:BiocubeFaceAPI:1.0'

}

   ``` 
## Authors

- [@Biocube]https://www.biocube.ai/)



## Documentation

[Documentation](https://docs.google.com/document/d/1-L7VNy39Iy0c40ASbJphIkWyPqW_QdiBFgI5HwcLN3o/edit?usp=sharing)


## Support

For support, email connect@biocube.ai or join our Slack channel.


## Private Policy
THIS DOCUMENT AND THE INFORMATION IN IT ARE PROVIDED IN CONFIDENCE, FOR THE SOLE PURPOSE OF EXPLORING BUSINESS OPPORTUNITIES BETWEEN BIOCUBE TECHNOLOGIES INC. AND THE RECEIVING PARTY CONCERNING IMPLEMENTATION OF BIOCUBE SOLUTIONS AND MAY NOT BE DISCLOSED TO ANY THIRD PARTY OR USED FOR ANY OTHER PURPOSE WITHOUT THE EXPRESS WRITTEN PERMISSION OF BIOCUBE TECHNOLOGIES INC.


