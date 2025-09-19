# ⭐ Star 本项目！
如果觉得本项目对你有帮助，请点击右上角的 ⭐Star 支持一下，感谢你的关注与支持！

---

## 📖 食用说明
- 一加内核开源地址：[OnePlusOSS](https://github.com/OnePlusOSS/kernel_manifest)

### 🔧 补丁概览
- ogki2gki.patch：单 boot 补丁
- ksu_manual_security_hooks_v1.4.patch：LSM 手动挂钩，适配 3.4–4.1，需 `CONFIG_KSU_LSM_SECURITY_HOOKS=n`
- ksu_scope_min_manual_hooks_v1.5.patch：最小范围 syscall 挂钩，GKI 4.19+，不依赖 kprobe

---

## 🏷️ 原始项目来源
- [@backslashxx/KernelSU#5 — scope-minimized manual hooks v1.5](https://github.com/backslashxx/KernelSU/issues/5) · 对应补丁：[ksu_scope_min_manual_hooks_v1.5.patch](https://github.com/FurLC/Action_OnePlus_KernelSU_SUSFS/blob/main/ksu_scope_min_manual_hooks_v1.5.patch)（GKI 4.19+，无需 kprobe）
- [@backslashxx/KernelSU#7 — manual security hooks v1.4](https://github.com/backslashxx/KernelSU/issues/7) · 对应补丁：[ksu_manual_security_hooks_v1.4.patch](https://github.com/FurLC/Action_OnePlus_KernelSU_SUSFS/blob/main/ksu_manual_security_hooks_v1.4.patch)（需 `CONFIG_KSU_LSM_SECURITY_HOOKS=n`）

---

## 📚 参考资料
### 内核
- [KSU-NEXT](https://github.com/KernelSU-Next/KernelSU-Next)
- [MKSU-SKN](https://github.com/ShirkNeko/KernelSU)

### Patch
- [1.patch](https://github.com/egcd123/boot/blob/main/1.patch)

---

感谢您的支持，祝您食用愉快！
