# 实施方案

Bifrost 将以 Polkadot 平行链的形式完成业务落地，与其他平行链共享 Polkadot 共识安全性。避免运营维护一个独立的公链网络的高额成本。独立的 PoS 公链网络运营成本是巨大的，以 Cosmos 为例，根据当前 72% 质押率和 8.09% 收益率来计算每年通胀率约为 5.8%，则每年维护网络安全成本大约需要 15,344,540 ATOM（约为 $83,474,302），维护安全成本是巨大的，如果网络用量较低、价值捕获能力不足，高额的通胀甚至会将网络推向死亡螺旋的窘境。

另一方面，Bifrost 当前从 Staking 衍生品切入为多数 PoS 网络提供流动性，势必导致多数 PoS 网络中原生资产及其对应票权在 Bifrost 协议中进行映射，而此类原生资产所对应的共识安全也相应被转移到了 Bifrost 网络中，若 Bifrost 共识安全攻击成本低于原 PoS 共识安全成本，将导致黑客有意通过攻击 Bifrost 网络来完成原 PoS 网络的攻击，这将使 Bifrost 网络不再被信任，甚至遭到其他 PoS 网络的技术反制，所以只有在 Bifrost 共识安全高于或等于原 PoS 网络时，Bifrost 协议在客观条件下才能为其他 PoS 网络提供 Staking 流动性。

所以 Bifrost 将竞拍波卡平行链卡槽，通过成为平行链共享波卡共识安全，一方面给予 Bifrost 所支持的其他 PoS 网络及平行链更多共识安全保障，另一方面，降低 Bifrost 为维护独立 PoS 网络共识安全所支出的高额成本。
