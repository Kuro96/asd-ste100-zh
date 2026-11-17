# 双语报告示例

以下为合成场景，每组材料是对应报告的事实基准。

## 排障与确定性

**材料**：日志包含错误码 `E01`；错误仅在重试期间被观察到；超时是可能原因，尚待确认。

**English**

> The log contains `E01`. The error was observed only during retries. The cause may be a timeout. The cause is unconfirmed.

**中文**

> 日志中出现 `E01`。目前仅在重试期间观察到该错误，原因可能是超时，尚待确认。

**要点**：错误码、观察范围和推测强度一致。

## 测量与范围

**材料**：硬件 A；50 次请求；解析阶段 p95 从 120 ms 降至 90 ms；测量覆盖解析阶段。

**English**

> 50 requests were measured on hardware A. For the parsing stage, p95 decreased from 120 ms to 90 ms. The measurements cover the parsing stage.

**中文**

> 在硬件 A 上测量了 50 次请求。解析阶段的 p95 从 120 ms 降至 90 ms；本次测量覆盖解析阶段。

**要点**：样本、环境、统计量、方向、单位与测量范围完整保留。

## 条件与要求强度

**材料**：校验和相同则允许加载；校验和不同则禁止加载；建议在下一次导入前检查产物。

**English**

> If the checksum matches, you may load the artifact. If the checksum differs, you must not load the artifact. You should inspect the artifact before the next import.

**中文**

> 校验和相同时可以加载产物；校验和不同时禁止加载。建议在下一次导入前检查产物。

**要点**：许可和禁止分别绑定各自条件，建议保留原有强度。
