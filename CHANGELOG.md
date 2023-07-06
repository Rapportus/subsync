# Changelog

All notable changes to this project will be documented in this file.

## 1.0.0 (2023-07-06)


### ⚠ BREAKING CHANGES

* Switch to using required inputs for better control (#6)

### Features

* add more flags to cli tool ([2d3e2e3](https://github.com/Rapportus/subsync/commit/2d3e2e3595fcc34d219b9525f6d303cf1b010b6b))
* added --graph flag ([48e5692](https://github.com/Rapportus/subsync/commit/48e56921689e188626d22f712818a502032acf1a))
* added ffmpeg module ([528df05](https://github.com/Rapportus/subsync/commit/528df051fd464d93cbd9557e02816b8fad088210))
* added init target in makefile ([d03a934](https://github.com/Rapportus/subsync/commit/d03a934c009c523c8932fefcb45cb03aea6e51e6))
* ann network model training ([253865e](https://github.com/Rapportus/subsync/commit/253865e84de1dd9308154022429afeedb80ea88e))
* auto-detect encoding see [#3](https://github.com/Rapportus/subsync/issues/3) ([39170d5](https://github.com/Rapportus/subsync/commit/39170d5b67a870c5b9b2af06ad007ab62dcda4b7))
* clean subtitles ([65d5168](https://github.com/Rapportus/subsync/commit/65d51689c15372fb84ed7b7bb2d2bc9be8b7ad99))
* feature extraction of audio ([a6b2038](https://github.com/Rapportus/subsync/commit/a6b203891f83a84cdacb6a7aee19da9c82a2611a))
* find minimum logloss and sync subtitle ([6479e47](https://github.com/Rapportus/subsync/commit/6479e4733114a81538780977b5c4015960f8d096))
* implemented media and neuralnet classes ([5744091](https://github.com/Rapportus/subsync/commit/57440911693a83bf18b011b7106dda3ca5c898f9))
* include feaults in cli help ([8fc00ee](https://github.com/Rapportus/subsync/commit/8fc00ee568f486f207e4fd8eea05fa8b73f02737))
* logfile cli argument ([670a55e](https://github.com/Rapportus/subsync/commit/670a55e5210c841e5ec2a135ce8d56c9cc742f17))
* logloss plot and test files ([aa412b5](https://github.com/Rapportus/subsync/commit/aa412b5acff8679727da362e7d7b6d2b92679925))
* make logloss ([773ac1c](https://github.com/Rapportus/subsync/commit/773ac1c44f1afe089b8f76d55a18f722bbe27180))
* option to seek to middle of media ([850c60d](https://github.com/Rapportus/subsync/commit/850c60daec5e263aeefb53c7cc4075cee0219fc3))
* recursively sync subtitles ([6925225](https://github.com/Rapportus/subsync/commit/6925225e764a7403a2e004ed0f894124fccd8028))
* subtitle class and sync (logloss plot) ([23c8c36](https://github.com/Rapportus/subsync/commit/23c8c36fe4e20cd2a93d3da2388a2edfac70b4f5))
* support .srt files as arguments ([04ab90e](https://github.com/Rapportus/subsync/commit/04ab90e5e993677bd8c5793e8124eed8b9f99677))
* Switch to using required inputs for better control ([#6](https://github.com/Rapportus/subsync/issues/6)) ([c03bc26](https://github.com/Rapportus/subsync/commit/c03bc268c866f6b7edf55038d2ede8570a2bc864))
* training accuracy/loss inspection ([2b42350](https://github.com/Rapportus/subsync/commit/2b423503908aa5dd4b5f2b8ca1102582e22e61fe))


### Bug Fixes

* add .mp4 files, check ffmpeg exit code ([ca8260f](https://github.com/Rapportus/subsync/commit/ca8260f7a28a033374187d9f9efb0969187bb1ea))
* allow any version of tensorflow ([7ddd3e1](https://github.com/Rapportus/subsync/commit/7ddd3e147786b2bb877f1b0dc59642321f29f6bf))
* balance data ([e11222b](https://github.com/Rapportus/subsync/commit/e11222b12b7122324aa456d334dbd7076262d9ff))
* catch runtime errors when calc logloss ([a022cc2](https://github.com/Rapportus/subsync/commit/a022cc27e54fc199d486c08ca2dfd9c430de495b))
* change encoding to utf-8 closes [#3](https://github.com/Rapportus/subsync/issues/3) ([3018a9c](https://github.com/Rapportus/subsync/commit/3018a9c456f9499a7f1fd9e2d16ad4dacc168cdd))
* downgrade tensorflow to 1.5.1 for windows ([34a4f0c](https://github.com/Rapportus/subsync/commit/34a4f0cc944c91180ee4e3c73b7007e9b738ea7b))
* ffmpeg start param ([b2d5243](https://github.com/Rapportus/subsync/commit/b2d524375c27c7e33ac12eaccfced37963efff85))
* ffmpeg subprocess on unix ([2f1f723](https://github.com/Rapportus/subsync/commit/2f1f7232427e2780a66779eb559e64779d36d70e))
* import matplotlib lazily ([93a6a36](https://github.com/Rapportus/subsync/commit/93a6a36dda6a27b253b14015a49270297b8db517))
* input dimentions did not match ([23e6fa2](https://github.com/Rapportus/subsync/commit/23e6fa25035d4175d897b929b8ad831d0aa6d012))
* insane spelling error ([09b201f](https://github.com/Rapportus/subsync/commit/09b201fb614e0bcd8bc73a5420e537f29a99d184))
* make module installable by pip ([2c5c67c](https://github.com/Rapportus/subsync/commit/2c5c67cfb31cbf4a9a9fdf98a0006eb387bb910b))
* media file names ([a2dfb2a](https://github.com/Rapportus/subsync/commit/a2dfb2a1811df3137be30167ef370ae8ab7bd77a))
* omit empty string in media paths ([4c7a9c2](https://github.com/Rapportus/subsync/commit/4c7a9c2f2d2e14f512186da9e8b6c44ca3e57aa5))
* remove unnecessary prints ([0ebec09](https://github.com/Rapportus/subsync/commit/0ebec092f00793665d9f60a42a4b9e619619184d))
* typo ([6085dc7](https://github.com/Rapportus/subsync/commit/6085dc702b104c6547d4e7f76ee6e9fd6ec70f8c))
* update makefile with twine ([e5ce40c](https://github.com/Rapportus/subsync/commit/e5ce40c877c4fb0d9c358e1b0a1e36b2a8b4c0a7))
* use absolute paths resolves [#2](https://github.com/Rapportus/subsync/issues/2) ([d9c3e6f](https://github.com/Rapportus/subsync/commit/d9c3e6ffa83cd623ade84b530c7db1764142b322))
* voice activity detection ([3673ce2](https://github.com/Rapportus/subsync/commit/3673ce21dc74364dbac644b740bfb8b2b536ea61))
* windows ffmpeg arguments ([e5ca00b](https://github.com/Rapportus/subsync/commit/e5ca00b9cee81035ea444c6f3f641a79e32feb31))

### [1.0](https://github.com/Rapportus/subsync/releases/tag/v1.0) (2023-07-05)

Initial release matching the functionality forked from https://github.com/tympanix/subsync
