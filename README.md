# Team_Racoon
유니티 스터디 및 게임 개발 

<code> 
// 1. 힘을 줘서 이동 
        rigid.AddForce(inputVec);

        // 2. 속도 제어 
        rigid.velocity = inputVec;

        // 3. 위치 이동 
        rigid.MovePosition(rigid.position + inputVec);
</code>
