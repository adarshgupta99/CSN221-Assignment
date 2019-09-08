# CSN221-Assignment
mov r0,0
mov r1,1
.loop:
   mov r2,r1
   mov r3,r1
   .loop1:
       .loop2:
           mul r4,r2,r2
           mul r5,r4,r2
           mul r6,r3,r3
           mul r7,r6,,r3
           mov r8,0
           add r9,r5,r7
           cmp r9 r1
           beq.countIncrease
           sub r3,r3,1
           cmp r3,0
           bgt.loop2
      sub r2,r2,0
      bgt.loop1
   cmp cnt 2
   bgt.exit
   add i i 1
   .cntIncrease:
       add cnt cnt 1
   .exit:
       exit
   mov cnt,0    
