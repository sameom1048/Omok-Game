# [네트워크] 소켓 프로그래밍을 이용한 Omok-Game
### `Java를 이용해 만든 온라인 오목게임 (Develop with Eclipse)`

## 실행 방법
- **OmokGameServer Run & Server Start Click!**
- **OmokGameClient Run**
- **Login & Enjoy the game!**

<details>
<summary>
  <strong>What features</strong>
</summary>
  <li>오목기능 (흑돌만 33 44 불가)</li>
  <li>무르기 기능</li>
  <li>방만들기</li>
  <li>관전 기능</li>
  <li>강퇴 기능(방장만)</li>
  <li>기권 기능</li>
  <li>채팅창 기능(+이모티콘)</li>
  <li>복기 기능</li>
</details>

<details>
  <summary>
  <strong>Protocol</strong>
</summary>
  <br>
  <table>
    <tr>
      <th scope="col">Protocol</td>
      <th scope="col">용도/내용</td>
      <th scope="col">Protocol</td>
      <th scope="col">용도/내용</td>
    </tr>
    <tr>
      <td>100</td>
      <td>로그인</td>
      <td>500</td>
      <td>방만들기 (관전 O)</td>
    </tr>
    <tr>
      <td>101</td>
      <td>로그아웃</td>
      <td>510</td>
      <td>방만들기 (관전 X)</td>
    </tr>
    <tr>
      <td>200</td>
      <td>채팅 메시지</td>
      <td>501</td>
      <td>방 접속</td>
    </tr>
    <tr>
      <td>201</td>
      <td>이모티콘</td>
      <td>502</td>
      <td>방 리스트</td>
    </tr>
    <tr>
      <td>300</td>
      <td>준비</td>
      <td>600</td>
      <td>무르기</td>
    </tr>
    <tr>
      <td>301</td>
      <td>강제 퇴장</td>
      <td>601</td>
      <td>무르기 yes</td>
    </tr>
    <tr>
      <td>302</td>
      <td>기권</td>
      <td>602</td>
      <td>무르기 no</td>
    </tr>
    <tr>
      <td>400</td>
      <td>나가기</td>
      <td>700</td>
      <td>착수</td>
    </tr>
    <tr>
      <td>401</td>
      <td>방장 나가기</td>
      <td>701</td>
      <td>게임 준비 완료</td>
    </tr>
    <tr>
      <td>402</td>
      <td>관전</td>
      <td>702</td>
      <td>게임 승리</td>
    </tr>
    <tr>
      <td>403</td>
      <td>관전 불가 (관전 불가 방)</td>
      <td>703</td>
      <td>흰 돌 부여</td>
    </tr>
    <tr>
      <td>404</td>
      <td>관전 불가 (게임 진행 중)</td>
      <td>704</td>
      <td>검정 돌 부여</td>
    </tr>
    <tr>
      <td>405</td>
      <td>관전자 게임 참여</td>
      <td>705</td>
      <td>준비 취소</td>
    </tr>
  </table>
  </details>

  ### 실행화면
<img src="https://github.com/sameom1048/Omok-Game/assets/55376152/7f89d4a5-ba1e-4b86-b6e6-93120355d2da.jpg" width="30%" height="30%"/>
<img src="https://github.com/sameom1048/Omok-Game/assets/55376152/acf8b8be-7c7f-479b-a673-85f9a8866bef.jpg" width="50%" height="50%"/>
