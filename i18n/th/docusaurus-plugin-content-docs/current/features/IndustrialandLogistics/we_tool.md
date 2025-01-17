---
sidebar_position: 9
---
# World Edit Tool 🪓

![WE Tools](\img\doc\features\we_tools\WE_Tool.gif)

:::warning
ต้องการแรงค์ Astral ขึ้นไป
:::

:::danger
ฟีเจอร์นี้อาจเป็นอันตรายได้ โปรดใช้งานอย่างระมัดระวัง!
:::

## Set Position Region

### ตำแหน่งพื้นที่ จุดที่ 1

```
Left Click เพื่อเซตตำแหน่งจุดที่ 1
```

### ตำแหน่งพื้นที่ จุดที่ 2

```
Right Click เพื่อเซตตำแหน่งจุดที่ 2 (Pos2)
```

## Commands

:::tip
วัสดุทั้งหมดจะต้องมาจากช่องเก็บของ ของผู้เล่น
:::

### /set

```
/set <material> เพื่อเซตพื้นที่โดยบล็อคที่ต้องการ
```

Description : เซตบล็อคทั้งหมดในพื้นที่

|  การใช้งาน   | คำอธิบาย           |
| :----------: | ------------------ |
| `<material>` | วัสดุที่จะทำการเซต |

### /replace

```
/replace <target> <material> แทนที่ด้วยวัสดุที่ต้องการ
```

Description : แทนที่บล็อคทั้งหมดในส่วนที่เลือกด้วยบล็อคอื่น

|  การใช้งาน   | คำอธิบาย                        |
| :----------: | ------------------------------- |
| `<material>` | วัสดุที่จะทำการเซต              |
|  `<target>`  | เลือกบล็อคที่จะให้เกิดการแทนที่ |

:::tip
เครื่องมือมีความเร็วและการใช้งานที่แตกต่างกัน

- `You don't have enough uses left! Need: <recharge>`
  - Uses: หมายถึงจำนวนบล็อกทั้งหมดที่จะถูกเซตและแทนที่ หากมีจำนวนนี้ไม่เพียงพอ ข้อความจะปรากฏขึ้นเพื่อระบุจำนวนการชาร์จที่ต้องการ
- `Operation complete! Used <material> blocks`
  - Used: แสดงถึงจำนวนวัสดุทั้งหมดที่ใช้ระหว่างการดำเนินการ
- Recharging: การใช้เครื่องมือสามารถชาร์จใหม่ได้โดย:

  - Shift + Left Click: This is a quick method to recharge the tool.
  - /upgrade: This is another option for recharging and upgrading the tool.
    :::

:::danger
Tool speed upgrades are currently unavailable.
:::

## World Edit Upgrades

<!--### Speed Upgrade

![Speed_Upgrade](/img/doc/features/we_tools/Speed_Upgrade.png)
Speed Upgrade: การอัปเกรดนี้ช่วยเพิ่มความสามารถด้านความเร็วของเครื่องมือ ซึ่งจะช่วยให้ผู้เล่นสามารถสร้างสิ่งต่าง ๆ ได้ด้วยความเร็วที่เพิ่มขึ้นดังนี้:

| ลำดับขั้น | `<material>`/s |     ค่าใช้จ่าย |
| :---- | -------------: | -------: |
| I     |            `5` |  ค่าเริ่มต้น |-->

### Uses Upgrade

![Uses_Upgrade](/img/doc/features/we_tools/Uses_Upgrade.png)
Uses Upgrade: การรีชาร์จนี้ใช้เพื่อวางบล็อค มีค่าใช้จ่าย 1 การชาร์จต่อบล็อคที่วาง ค่าใช้จ่ายรีชาร์จจะแสดงดังต่อไปนี้

| ปุ่มกด              | รีชาร์จ | ค่าใช้จ่าย |
| ------------------- | ------: | ---------: |
| Left Click          |      +1 |         5$ |
| Shift + Left Click  |     +10 |        50$ |
| Right Click         |    +100 |       500$ |
| Shift + Right Click |   +1000 |      5000$ |

## History

| Date | [Lamalia Release](/patchNotes) | Description |
|-------------|-----------|-------------|
| 12/01/2025 | [2.2.0](/patchNotes#patch-220) | - Added: Worldedit tools to Beta Testers. |