<div align="center">
    
    mov [rax + 16], rbx
    lea rbx, fixup
    mov [rax], rbx
    mov rbx, rax   
    jmp r10

</div>