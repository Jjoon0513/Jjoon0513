
```rust
enum Me { Hug }

fn give(me: Me) {
    println!("{}", if let Me::Hug = me { "Give me HUG 🤗" } else { "" });
}

fn main() { give(Me::Hug); }
```

<div align="center">


# 안녕하신감! 👋

**4년차 저수준 · 시스템 프로그래머**

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=for-the-badge&logo=assemblyscript&logoColor=white)](https://nasm.us/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jjoon0513&layout=compact&hide=html,css&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

[![wakatime](https://wakatime.com/badge/user/ba63e96e-b35f-44b5-a94c-325c1a6b2c31.svg)](https://wakatime.com/@ba63e96e-b35f-44b5-a94c-325c1a6b2c31)

</div>

---

## 🖥️ 코딩으로 무엇을?

<table>
<tr>
<td width="33.3%">

### 🦀 Rust

```rust
fn main() {
    println!("Hello! Jjoon!");
}
```
거의 모든 프로젝트에 주로 사용

</td>
<td width="33.3%">

### ⚙️ Assembly

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

**NASM** 주력 · **GAS** (AArch64, x86-64)  
Rust 연계 / 언어 제작 / 컴파일러 작성

</td>
<td width="33.3%">

### 🐍 Python — AI 작업용

```python
if __name__ == '__main__':
    print("Hello! Jjoon!")
```

주로 사용하**던** 언어
지금은 AI 모델 작업에 사용합니다.

</td>
</tr>
</table>

---

## 😎 대표 프로젝트

<table>
<tr>
<td align="center" width="33.3%">

[![CherryBlossom](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=CherryBlossom&theme=dark)](https://github.com/Jjoon0513/CherryBlossom)

**🌸 Cherry Blossom**  
직접 설계한 정적 타입 컴파일 언어.  
타입 추론 없이 명시적 타입만 허용하며,  
코드를 예술처럼 아름답게 작성하는 것을 철학으로 삼습니다.

</td>
<td align="center" width="33.3%">

[![rustVM](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=rustVM&theme=dark)](https://github.com/Jjoon0513/rustVM)

**⚙️ rustVM**  
Rust(`no_std`)로 작성한 커스텀 가상 머신.  
16개의 범용 레지스터, 64KB 메모리 버스,  
권한 시스템과 MMIO 디바이스까지 직접 구현 중.

</td>
<td align="center" width="33.3%">

[![Lucid](https://github-readme-stats.vercel.app/api/pin/?username=Jjoon0513&repo=Lucid&theme=dark)](https://github.com/Jjoon0513/Lucid)

**💡 Lucid**  
AI 생성 코드를 위해 설계된 중간 언어. 
외부 함수 시그니처를 파일 안에서 완전히 선언해
AI의 추측을 원천 차단합니다.

</td>
</tr>
</table>

---

<div align="center">

$$bug_n = \left(\frac{coffee}{sleep}\right)^n + \text{Jjoon}, \quad n \in \mathbb{N}, \quad \text{Jjoon} = \text{Me}$$

</div>
