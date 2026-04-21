

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jjoon0513&layout=compact&hide=html,css)](https://github.com/anuraghazra/github-readme-stats)

[![wakatime](https://wakatime.com/badge/user/ba63e96e-b35f-44b5-a94c-325c1a6b2c31.svg)](https://wakatime.com/@ba63e96e-b35f-44b5-a94c-325c1a6b2c31)

```rust
enum Me {
    Hug,
}

fn give(me: Me) {
    println!("{}", if let Me::Hug = me { "Give me HUG" } else {""});
}

fn main() {
    give(Me::Hug);
    
}
```
# 안녕하신감! 👋
저는 코딩 3년차 저수준, 시스템 프로그래머 :)  
현재 다루는 언어는 **Python, Rust, Assembly** 입니다!

# 대표 프로젝트들 😎
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=CherryBlossom)](https://github.com/Jjoon0513/CherryBlossom)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=micro)](https://github.com/Jjoon0513/micro)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=Lucid)](https://github.com/Jjoon0513/Lucid)

# 코딩으로 무엇을 주로..? 🖥️

### Rust
```rust
fn main(){
    println!("Hello! Jjoon!");
}
 ```
주로 사용하는 언어입니다

### Assembly {Nasm(주로 사용), Gas(AArch64, x86-64)}
```asm
section .data
    msg db "Hello! Jjoon!", 10
    len equ $ - msg

section .text
    global _start

_start:
    mov rax, 1
    mov rdi, 1
    mov rsi, msg
    mov rdx, len
    syscall

_exit:
    mov rax, 60
    xor rdi, rdi
    syscall
```
매우 저수준을 다룰때 사용합니다 보통 **Rust**와 연계하거나 새로운 언어 제작, MCP를 프로그래밍 할때 사용합니다

### Python

```python
if __name__ == '__main__':
    print("Hello! Jjoon!")
```
주로 사용하**던** 언어입니다.
파이썬으로는 AI를 주로 작업합니다


---
$$
\begin{aligned}
bug_n &= \left(\frac{coffee}{sleep}\right)^n + \text{Jjoon} \\
n &\in \mathbb{N} \\
\text{Jjoon} &= \text{Me}
\end{aligned}
$$
