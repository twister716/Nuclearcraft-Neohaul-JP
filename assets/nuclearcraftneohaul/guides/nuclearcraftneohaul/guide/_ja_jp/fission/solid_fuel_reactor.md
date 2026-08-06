---
navigation:
  title: 固形燃料核分裂炉
  icon: solid_fuel_fission_controller
  parent: fission/fission.md

item_ids:
  - solid_fuel_fission_controller
---

# 固形燃料核分裂炉

固形燃料核分裂炉（SFR）は、ペレット状の固形核分裂燃料を用いた核分裂炉である。反応によって発生した熱は液体冷却材を気化させ、[タービン](../multiblocks/turbine.md)で電気に変換される。

#### 核反応燃料

SFRでは、アイテムの形態を取る核燃料ペレットを核反応燃料として使用し、核燃料は<ItemLink id="fission_fuel_cell_port" />を通して<ItemLink id="fission_fuel_cell" />に搬入される。

例として低濃縮ウラン(LEU)235を使用する場合：
<Row>
<RecipesFor id="leu_235" />
</Row>

以下の核燃料ペレットに加工可能である：

<ItemGrid>
<ItemIcon id="leu_235_za" />
<ItemIcon id="leu_235_ox" />
<ItemIcon id="leu_235_ni" />
</ItemGrid>

それぞれに固有の特性が存在しており、同じ核燃料種でも異なる構成の原子炉が必要となる。

#### 冷却

SFRは通常、<FluidLink id="minecraft:water" />を冷却材として使用する。使用された<FluidLink id="minecraft:water" />は<FluidLink id="high_pressure_steam" />へと気化し、[タービン](../multiblocks/turbine.md)によって電気へと変換される。