Common Extensibility Platform (CEP) 시작하기
==============

이 페이지는 Adobe Creative Cloud 애플리케이션용 확장 기능을 만들기 위해 필요한 [시작 가이드](https://github.com/Adobe-CEP/Getting-Started-guides) 리소스를 제공합니다. 새로운 HTML5/JavaScript 인터페이스 모델을 사용합니다. Flash/ActionScript 인터페이스 모델은 Creative Cloud 릴리스에서 더 이상 사용되지 않으며, CC2014 이후 버전에서는 이미 지원이 중단되었습니다.

* CEP 12는 최신 Creative Cloud 애플리케이션의 확장 기능과 애드온 개발에 사용할 수 있습니다. CEP 12와 통합된 Creative Cloud 제품은 이 [표](./CEP_12.x/Documentation/CEP%2012.1%20HTML%20Extension%20Cookbook.md#applications-integrated-with-cep)를 참조하세요.

* CEP 11은 최신 Creative Cloud 애플리케이션의 확장 기능과 애드온 개발에 사용할 수 있습니다. CEP 11과 통합된 Creative Cloud 제품은 이 [표](./CEP_11.x/Documentation/CEP%2011.1%20HTML%20Extension%20Cookbook.md#applications-integrated-with-cep)를 참조하세요.

* CEP 10은 최신 Creative Cloud 애플리케이션의 확장 기능과 애드온 개발에 사용할 수 있습니다. CEP 10과 통합된 Creative Cloud 제품은 이 [표](./CEP_10.x/Documentation/CEP%2010.0%20HTML%20Extension%20Cookbook.md#applications-integrated-with-cep)를 참조하세요.

* Creative Cloud 2019 제품에는 확장 기능과 애드온 개발을 위한 CEP 9가 포함되어 있습니다. 2019 제품과 CEP 9의 통합은 이 [표](./CEP_9.x/Documentation/CEP%209.0%20HTML%20Extension%20Cookbook.md#applications-integrated-with-cep)를 참조하세요.

이 SDK는 확장 기능을 구축하는 데 필요한 저수준 도구를 제공합니다. 이러한 도구로 만든 확장 기능은 Extension Manager에서 인식하고 로드할 수 있도록 ZXP 파일로 패키징해야 합니다. 확장 기능을 마케팅 포털(Adobe Exchange, Add-ins 웹사이트, Creative Cloud 데스크톱 앱)을 통해 무료 또는 유료 제품으로 제공할 수 있습니다. 이때 확장 기능을 단일 ZXP 파일로 Adobe에 업로드합니다.

필요한 리소스:
* 운영 체제, Extension Manager와의 통신 및 호스트 애플리케이션과 다른 확장 기능과의 통신을 위한 CEP JavaScript 라이브러리
* 이러한 라이브러리 사용 방법에 대한 샘플 코드
* 명령줄 유틸리티인 ZXP 패키저

---

Creative Cloud 호스트 애플리케이션용 CEP 12.0 HTML/JavaScript 확장 기능 개발하기

**문서**

  * **[HTML 확장 기능 쿡북](./Documentation/README.md)**
  
  * **API**
    CEP 12 API:
      * API를 사용해야 하는 경우 확장 기능 프로젝트에 다음 파일을 포함하세요.
          * CSInterface.js
          * Vulcan.js
      * 다음 파일은 확장 기능 프로젝트에 포함하지 마세요. 이미 CEP에 통합되어 있습니다.
          * CEPEngine_extensions.js

  * **[Sample extensions](https://github.com/Adobe-CEP/Samples)** 
    

  * **Packaging and Signing Tool (ZXPSignCMD)**
    * Tool: [ZXPSignCMD](https://github.com/Adobe-CEP/CEP-Resources/tree/master/ZXPSignCMD)
    <!--- * Document: [Packaging and Signing Adobe Extensions](https://github.com/Adobe-CEP/CEP-Resources/blob/master/ZXPSignCMD/SigningTechNote_CC.pdf) ---> 

  * **Extension Installation Tools** 
    * Extension Manager Command Line Tool
      * [Announcement: Extension Manager End of Life](https://www.adobeexchange.com/resources/27)
      * [ExMan Command Line Tool](https://www.adobeexchange.com/resources/28)
      * [ExMan Command Line Tool's Error Codes](http://www.adobeexchange.com/resources/19#errors)
    * [A Python script to install & manage extensions](https://github.com/adobe-photoshop/generator-panels/blob/master/installPanels.py) (by John Peterson)
    * Other Tools
      * http://zxpinstaller.com/
      * http://install.anastasiy.com/

  * **Tooling** 
    * [Extension Builder 3 Preview](http://adobe.ly/1pho2QU)
    * [Extension Builder 3 forums - get help from the developer community](http://adobe.ly/1mgZ2xe)
   (NOTE: EB3 is compatible with CEP 4.x only. You can [tweak it](http://adobe.ly/1v3wgiq) so that it supports CC 2014 (with limitations))

  * **[Older CEP versions 4.x to 7.x](./README_ArchivedVersions.md)**


----


**Miscellaneous help**
* [Getting Started Guides](https://github.com/Adobe-CEP/Getting-Started-guides)
* [CS SDK Blog](https://blogs.adobe.com/cssdk/)
* [Andy Hall's Super Mega Guide (English)] (http://bit.ly/XQn9IV) [ (Japanese)] (http://bit.ly/XQnB9P)
* [Davide Barranca's blog](http://www.davidebarranca.com/) and [HTML Panels Development Course](http://htmlpanelsbook.com/)
* [David Deraedt's plugin for Adobe Brackets](http://bit.ly/QKWWYL)
* [Olav Martin Kvern's article on extensibility and InDesign](http://bit.ly/1zEa9Ef)
* [The other API (Article on Medium)](http://bit.ly/1hIFZay)
* [Adobe Exchange](http://bit.ly/1mHVksI)
* [Photoshop CC 2014 CEP samples by John Peterson](http://bit.ly/1nGAWYN)

----

**License**
* [English](./License/GenSDK_IHC-en_US-20120323_1224.pdf)
* [French](./License/GenSDK_IHC-fr_FR-20120323_1224.pdf)

----



