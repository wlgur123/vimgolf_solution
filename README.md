# vimgolf_solution

## Problem_1

G (제일 뒷 라인으로 커서 이동) -> 
W (다음 단어 앞으로 이동) ->
i (입력모드 전환) -> 
End (라인의 가장 뒤로 이동) ->
ZZ (저장하고 닫기)


![vimgolf_1](https://user-images.githubusercontent.com/94299473/144712580-9b7474c5-d2b4-4aa3-ad4b-b50701dc01a4.gif)

![vimgolf_result1](https://user-images.githubusercontent.com/94299473/144712747-c359c4cf-779e-4bb5-9f0c-dfcec6ffda3b.jpg)

## Problem_2

:%s/sublime\|emacs/vim/g (sublime 과 emacs를 vim으로 치환) (전체범위로 적용)


![vimgolf_2](https://user-images.githubusercontent.com/94299473/144713017-8695bb14-20cd-4faa-917f-4f8443723fe8.gif)


![vimgolf_result2](https://user-images.githubusercontent.com/94299473/144712798-0344a2fe-b55b-45a9-9b6d-ec21ccb93964.jpg)


## Problem_3

4G (4번 라인으로 커서 이동) ->
yw (현재 단어 단위로 복사) ->
O (현재 라인을 다음 줄로 밀고 입력 모드 시작) ->
// (입력) ->
esc (입력모드 탈출) ->
p (Version단어 붙여넣기) ->
a (현재 위치 다음 칸에서 입력 모드 시작) ->
TODO (입력) ->
esc (입력모드 탈출) ->
ZZ (저장하고 닫기)


![vimgolf_3](https://user-images.githubusercontent.com/94299473/144713052-5fd1e493-b9ae-4b23-aa4a-43fc65665dfb.gif)


![vimgolf_result3](https://user-images.githubusercontent.com/94299473/144712945-e81c93e5-15f7-4e20-bff6-34fab07599d2.jpg)


## Problem_4

/y (y문자 찾기) ->
enter ->
Ctrl v (비주얼 블록 모드) ->
I (블록 삽입 모드) ->
abs( (입력) ->
/, (,문자 찾기) ->
Enter ->
Ctrl v (비주얼 블록 모드) -> 
I (블록 삽입 모드) ->
) (입력) ->
:3s/k/b (k를 b로 치환) ->
:3s/1/2/g (1을 2로 치환) ->
:4s/k/r (k를 r로 치환) ->
:5s/k/g (k를 g로 치환) ->
:5s/1/4/g (1을 4로 치환)


![vimgolf_4](https://user-images.githubusercontent.com/94299473/144713058-79f7a571-455e-4685-bd94-a79905b8c825.gif)


![vimgolf_result4](https://user-images.githubusercontent.com/94299473/144712956-04f34b3a-8807-4ad3-ab9d-c6f5ea26640c.jpg)


## Problem_5
5G (5번째 라인으로 이동) ->
yw (현재 단어 복사) ->
10G (10번째 라인으로 이동) ->
End (라인 가장 뒤로 이동) ->
p (복사한 단어 붙여넣기) ->
a (현재 위치 다음 칸에서 입력 모드 시작)


![vimgolf_5](https://user-images.githubusercontent.com/94299473/144713065-af364075-3423-49e8-a861-02b13caa825b.gif)


![vimgolf_result5](https://user-images.githubusercontent.com/94299473/144712964-a5311418-a881-4158-a70d-da70d5ca7a8c.jpg)

