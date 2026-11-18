# G☢️Nuclear Kernel

<img width="1536" height="768" alt="17733281331994800817939737647968" src="https://github.com/user-attachments/assets/7bc036b5-e535-4684-9ff6-d3511f81d7c2" />


**[Download Kernel (Normal)](https://github.com/IamCharvik/GoNuclear-Kernel-Releases/releases)**

**[Download Kernel (KSU)](https://github.com/IamCharvik/GoNuclear-Kernel-Releases/releases)**


### Changelog V5.0

- Backported SBalance IRQ balancer along with IRQ affinity and hotplug fixes
- Backported BORE Scheduler 7.0.0/7.0.1 and integrated it into EEVDF
- Eager wakeup preemption and eager yield on slice protection expiry
- Backported timer subsystem overhaul (pull-model timer wheel, timer_shutdown)
- LMh hw-throttle routed through FIE along with cpufreq qcom-hw stability fixes
- Backported VMA/mmap write-locking fixes from linux-6.12.y
- Backported RCU nocb deferred wakeup requeue fix and lazy preempt/SLUB fixes
- Backported kgsl GPU fixes
- Fix camera rear portrait power-up and camera dtbo build
- Fix RPM panic
- Sync LineageOS 24 base + CLO/msm sources (incl. upstream security fixes)
- Built with clang-r614150

#### KSU build

*Everything in the normal build, plus:*

- KernelSU (BakaSU fork), formerly known as ReSukiSU.
- The KSU-Manager built directly from source with the INTERNET permission removed.
- Only the exact manager APK we build and offical KSU-Manager is allowed to get root.
- Manual hooks enabled (setuid / initrc / input) for 5.4 non-GKI kernels
- Multi-manager support removed

### 📱 Supported Devices
* STONE/GEMSTONE (Redmi Note 12 5g × Poco X5 5g)

### ⚙️ Supported ROMs
* AOSP ROMS ONLY

---
*Please refer to our Telegram Support Group for more info & questions.*
