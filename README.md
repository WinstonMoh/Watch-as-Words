### Cognitive-Speech-STT-ServiceLibrary - `Closed Captioning Creator`

Go here for How-to:
https://docs.microsoft.com/en-us/azure/cognitive-services/speech/getstarted/getstartedcsharpservicelibrary

## Introduction
CC Creator is a program which converts videos with no subtitles to one with subtitles. It leverages the robustness of the Bing Speech Microsoft with C# to achive that. 
@author: Winston Moh T.
         Kitty Liu
@Bitcamp

## Table of Contents
[Prerequisites](#prerequisites)<br/>
[Get API Key](#get_api_key)<br/>
[Install the sample application](#install_the_sample_application)<br/>
[Build the sample application](#build_the_sample_application)<br/>
[Run the sample application](#run_the_sample_application)<br/>

## <a name="prerequisites"></a>Prerequisites
Platform requirements
The following example was developed for Windows 10 and .NET 4.5+ Framework by using Visual Studio 2017, Community Edition.

## <a name="get_api_key"></a>Get API Key
Subscribe to the Speech Recognition API, and get a free trial subscription key.
The Speech API is part of Cognitive Services (previously Project Oxford). You can get free trial subscription keys from the Cognitive Services subscription page. After you select the Speech API, select Get API Key to get the key. It returns a primary and secondary key. Both keys are tied to the same quota, so you can use either key.

## <a name="install_the_sample_application"></a>Install the sample application
Start Visual Studio 201x, and select File > Open > Project/Solution.

Double-click to open the Visual Studio 201x Solution (.sln) file named SpeechClient.sln. The solution opens in Visual Studio.

## <a name="build_the_sample_application"></a>Build the sample application
Press `Ctrl+Shift+B`, or select Build on the ribbon menu. Then select Build Solution.

## <a name="run_the_sample_application"></a>Run the sample application
After the build is finished, press F5 or select Start on the ribbon menu to run the example.

Open the output directory for the sample, for example, SpeechClientSample\bin\Debug. Press `Shift+Right-click`, and select Open command window here.

Run `SpeechClientSample.exe` with the following arguments:

  Arg[0]: Specify an input audio WAV file. Place .wav file in same folder as .exe file.

  Arg[1]: Specify the audio locale. example: "en-us"

  Arg[2]: Specify the recognition modes: Short for the `ShortPhrase` mode and Long for the `LongDictation` mode.

  Arg[3]: Specify the subscription key to access the speech recognition service.
