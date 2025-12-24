# 다빈치리졸브 기본 조작부터 색보정까지

### ◆ 프로그램 정보
| 분류 | 상세|
|---|---|
| 제작사 | ![BlackMagicDesign](https://github.com/SamakFOX/Davinci-Resolve/blob/main/image/DVC_Logo.png) |
| 최신버전 | 20.3.1 (25년12월 기준) |
|  |  |

메이저 업데이트 시 (ex. 19 → 20), 일부 기능이 변경/삭제/통합되거나 툴바 위치와 기능이 달라질 수 있습니다.  
업데이트 시에는 커뮤니티를 통해 후기와 변경 로그를 확인 후 업데이트하시는 것을 추천드립니다.  
> 특히 실무에서는 해당 스튜디오에서 워크플로가 잡혀있는 버전을 유지하는 것이 좋습니다.  

&nbsp;
### ◆ 프로그램 다운로드 및 설치  
[블랙매직디자인 공식 홈페이지](https://www.blackmagicdesign.com/products/davinciresolve) 를 통해 인스톨러 다운로드 및 설치  
> 무료 버전으로도 4K 출력과 많은 기능을 사용할 수 있어 처음 접할 시 무료 사용도 괜찮습니다.  
> 하지만 작업 시 도움이 되는 기능들이 Studio에서 제공되는 점과,  
> 타 전문분야 프로그램들과 비교했을 때, 영구라이선스로 버전업도 무료이며 가격도 비교적 세지 않기 때문에 구매를 고려해보는 것도 좋습니다.  

![Studio](https://github.com/SamakFOX/Davinci-Resolve/blob/main/image/DVC_Studio.png)

| 분류 | 무료 | Studio |
|---|:---:|:---:|
| 최대 해상도/프레임 | UHD 4K 60fps | 최대 32K / 120fps 지원 |
| AI 기능 (매직 마스크 등) | 일부 제한 | 전체 |
| 고급 노이즈 리덕션 | ❌ | ✔️ |
| 10비트 / 8K 지원 | ❌ | ✔️ |
| 멀티 GPU 가속 | ❌ | ✔️ |
| HDR & 프로 색보정 도구 | 기본 | 향상 버전 |
| 협업/프로 워크플로 | 제한 | 협업위주 |

정보 출처 : https://artlist.io/blog/davinci-resolve-free-vs-studio

&nbsp;
### ◆ 기초 사용법
#### * Studio 18버전으로 작성되었습니다.

▶ Resolve & 프로젝트 설정  
&nbsp;&nbsp; - 기본적으로 UI,프로젝트,소스에는 <mark>영어와 하이픈,언더바</mark> 위주로 사용하는 것이 좋습니다.  
&nbsp;&nbsp;&nbsp;&nbsp; (오류 방지, 해외 튜토리얼 습득 등 여러 사유, 특히 MAC의 경우 공백도 기호로 인식하므로 필수)  

★ 설정  
&nbsp;&nbsp; - 설정은 `User`와 `System`으로 나뉨  
&nbsp;&nbsp; - User : 

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/SamakFOX/Davinci-Resolve/blob/main/image/DVC_Settings1.png" width="600"><br>
      <em> '설정' 내 'UI'탭 </em>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/SamakFOX/Davinci-Resolve/blob/main/image/DVC_Settings2.png" width="600"><br>
      <em> '설정' 내 'Save and Load'탭 </em>
    </td>
  </tr>
</table>

▶ 프로젝트 생성  
&nbsp;&nbsp; - 다빈치리졸브 실행 시 초기메뉴로 **프로젝트 윈도우**가 뜸  
&nbsp;&nbsp; - New Project 버튼 클릭하여 새 프로젝트 생성 (되도록 영어로 작성)  
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/SamakFOX/Davinci-Resolve/blob/main/image/DVC_NewProject.png" width="600"><br>
      <em> 프로젝트 윈도우 → 새 프로젝트생성 </em>
    </td>
  </tr>
</table>
