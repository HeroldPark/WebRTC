# WebRTC Code Samples

```
git clone https://github.com/webrtc/samples
```

This is a repository for the WebRTC JavaScript code samples. All of the samples can be tested from [webrtc.github.io/samples](https://webrtc.github.io/samples).

To run the samples locally
```
npm install && npm start
```
and open your browser on the page indicated.

## Contributing
We welcome contributions and bugfixes. Please see [CONTRIBUTING.md](https://github.com/webrtc/samples/blob/gh-pages/CONTRIBUTING.md) for details.

## Bugs

If you encounter a bug or problem with one of the samples, please submit a
[new issue](https://github.com/webrtc/samples/issues/new) so we know about it and can fix it.

Please avoid submitting issues on this repository for general problems you have with WebRTC. If you have found a bug in
the WebRTC APIs, please see [webrtc.org/bugs](https://webrtc.org/support/bug-reporting) for how to submit bugs on the affected browsers.
If you need support on how to implement your own WebRTC-based application, please see the
[discuss-webrtc](https://groups.google.com/forum/#!forum/discuss-webrtc) Google Group.

```
echo "# WebRTC" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:HeroldPark/WebRTC.git
git push -u origin master
```

### 1. 2024-10-06
    - package.json에서 별도로 webrtc 관련 module 설치는 없다.
    - crome browerse에서 제공되는 것으로 이용한다.

### 2. 2024-10-07
    - src/peerconnection 분석 : video4 추가
    - 