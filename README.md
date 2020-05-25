# Linux_homework
Linux_homework<br />
<del>나는 리눅스가 싫어요.</del><br />
Github상에서 PR을 보내보는 실습을 해봅시다.<br />
relay_coding이나 relay_novel 폴더에 자유롭게 작성해주시면 됩니다.

# relay_coding
relay_coding 폴더에는 여러분들이 자유롭게 코드를 이어서 작성해 주시면 됩니다!<br />
printf만 하는 코드여도 상관 없습니다..

# relay_novel
relay_novel 폴더에는 여러분들이 자유롭게 소설을 작성해주시면 됩니다.<br />
어떤 소설이 나올지 벌써부터 궁금합니다!

# PR을 보내기 전 (중요)<br />
여러분이 작업하는 동안 이 repo에는 다른 학생들이 PR을 보낸 코드가 업데이트 되게 됩니다.<br />
그렇기 때문에 여러분이 PR을 보낼 쯤에는 작업하던 코드와 다른 코드가 있으므로 `conflict`가 일어나겠죠?<br />
그런 경우에는 PR을 받아줄수가 없습니다..<br />
그렇기 때문에 다음 과정을 거쳐서 `merge`가 이루어진 다른 코드를 업데이트하는 과정을 거치도록 합니다.<br />
## 리모트 저장소 추가
`git remote add lamp https://github.com/lampkang/linux_homework`<br />
위 명령어를 터미널에 입력하면 fetch를 받아올 리모트저장소를 등록합니다.<br />

## fetch
`git fatch lamp`
<B>브랜치를 변경하지 않았다면</B> <br />여러분의 `master`에 이 저장소의 코드가 `fetch` 명령을 통해 업데이트가 됩니다.
## merge
`git merge lamp/master`<br />
fetch를 하였으니 merge를 통하여 여러분의 코드와 통합시키도록 합니다.<br />
conflict가 일어날 수 있으니 잘 해결해보시길 바랍니다!
## PR
conflict가 해결되었다면 이제 PR을 보내셔도 좋습니다!

# 주의사항
- star와 watch는 안눌러주셔도 됩니다.<br />
- 이 repo는 언젠가 삭제될 예정입니다.(아마도 제출마감 후?)<br />
- conflict가 일어난다면 해결해주셔야 PR이 받아들여집니다.<br />
- <B>PR을 하기 전, fetch를 하여 conflict가 일어나는지 확인하도록 합시다.</B><br />
- 다른 사람이 작성한 코드는 왠만 하면 삭제하지 말고 수정만 살짝씩 하도록 합니다.

# 참고사항
- commit message는 구체적으로 써주시는게 좋습니다. <br />
- 여러분이 작성한 코드 내역은 본 조교가 열심히 확인하고 반영하고 있습니다. <br />
