readme..
git 수업내용입니다.

일부 설명사항 저장용 

reset _ mixed : 지금 사용사는 working copy 는 uncommit 으로 되고 
				이전 버전은 삭제됨
reset _ hard : 모든 이전버전이 삭제됨
revert (reverse commit) : commit 했던 이전 사항으로 돌아오면서
						삭제하지는 않고 [Revert ****]로 새로 저장됨
						몇단계를 한번에 넘길 수는 없고
						하나씩 역순으로 내려가면서 revert 실행해야함
						결국 현 버젼을 유지하면서 이전 상태로 되돌아감..

branch : 수정사항을 양쪽에서 관리하려할때
		[branch] icon 을 click 
		왼쪽 menu bar 에 branch 를 보면 활성상태가 체크마크로 표시됨
		각각의 branch에서 수정사항은 따로따로 저장됨