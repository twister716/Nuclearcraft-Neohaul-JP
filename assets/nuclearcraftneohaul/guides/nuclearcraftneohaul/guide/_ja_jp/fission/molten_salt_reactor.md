---
navigation:
  title: 溶融塩核分裂炉
  icon: molten_salt_fission_controller
  parent: fission/fission.md

item_ids:
  - molten_salt_fission_controller
---

# 溶融塩核分裂炉

溶融塩核分裂炉（MSR）は、液体状の核分裂燃料を用いた核分裂炉である。反応によって発生した熱は溶融塩冷却材を加熱し、[熱交換器](../multiblocks/heat_exchanger.md)で水に伝達され、蒸気を生み出す。

#### 核反応燃料

MSRでは、液体の形態を取るFLiBe溶融塩を核燃料として使用し、<ItemLink id="fission_fuel_vessel_port" />を通して搬入される。

例：
<FluidLink id="leu_235_fluoride_flibe" />は<FluidLink id="depleted_leu_235_fluoride_flibe" />に劣化する。

#### 冷却

MSRは、<FluidLink id="gold_nak" />などのナトリウム・カリウム共晶混合液で冷却され、<FluidLink id="gold_nak_hot" />が生成される。これは[熱交換器](../multiblocks/heat_exchanger.md)で水と熱交換され、元の冷却用溶液に戻る。