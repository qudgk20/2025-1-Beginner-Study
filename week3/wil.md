pull - 깃허브와 로컬 컴퓨터 사이의 싱크 맞추기.
git checkout main 
git pull origin main
git log - commit 했던 기록들 확인할 수 있음.
head - 현재 작업 중인 위치.
git status - 상태에 따라 파일을 분류하여 확인.
commit 되돌리기, 없애기 알아봄.
amend - 마지막 commit 내용 변경, 새로운 commit으로 대체.
'-m'으로 vim 없이 commit 수정.
'--no-edit'으로 commit 메세지 수정 없이 commit 수정.
*amend - 혼자 사용하는 branch에서만 사용할 것.
reset - commit 제거. soft, mixed, hard 존재.
mixed가 default.
soft - commit만 취소. 수정된 파일이 staging area로 돌아감.
mixed - commit 취소. working directory로 돌아감.
hard - commit 취소. 변경사항 폐기.
revert - commit 제거 안하고 되돌림.