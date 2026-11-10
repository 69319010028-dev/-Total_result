---
name: Directory & Link Portal
description: ไดเรกทอรีและพอร์ทัลศูนย์รวมลิงก์บุคลากรระดับมืออาชีพ
colors:
  primary: "#4f46e5"
  primary-glow: "rgba(79, 70, 229, 0.35)"
  primary-hover: "#6366f1"
  bg-dark: "#0b1120"
  bg-deep: "#0f172a"
  surface-wrapper: "rgba(255, 255, 255, 0.92)"
  surface-card: "#ffffff"
  surface-card-hover: "#fdfdfd"
  surface-input: "#f8fafc"
  border-subtle: "#eef2f6"
  border-field: "#e2e8f0"
  text-main: "#0f172a"
  text-body: "#1e293b"
  text-sub: "#64748b"
  text-muted: "#94a3b8"
  status-online: "#10b981"
  badge-verified: "#3b82f6"
typography:
  display:
    fontFamily: "Prompt, sans-serif"
    fontSize: "30px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Prompt, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.25
  title:
    fontFamily: "Prompt, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.3
  body:
    fontFamily: "Prompt, 'Plus Jakarta Sans', sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.02em"
rounded:
  xs: "6px"
  sm: "14px"
  md: "16px"
  lg: "18px"
  xl: "20px"
  xxl: "32px"
  full: "9999px"
spacing:
  xs: "6px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
components:
  button-open:
    backgroundColor: "{colors.surface-input}"
    textColor: "{colors.text-sub}"
    rounded: "{rounded.sm}"
    padding: "0"
    height: "40px"
    width: "40px"
  button-open-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "#ffffff"
    rounded: "{rounded.sm}"
    padding: "0"
    height: "40px"
    width: "40px"
  member-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.text-main}"
    rounded: "{rounded.xl}"
    padding: "16px 20px"
  search-input:
    backgroundColor: "{colors.surface-input}"
    textColor: "{colors.text-body}"
    rounded: "{rounded.md}"
    padding: "14px 20px 14px 48px"
  tag-role:
    backgroundColor: "#f1f5f9"
    textColor: "#475569"
    rounded: "{rounded.xs}"
    padding: "2px 8px"
---

# Design System: Directory & Link Portal

## Overview

**Creative North Star: "The Professional Atelier"**

ระบบการออกแบบ "The Professional Atelier" สื่อถึงสตูดิโอระดับผู้เชี่ยวชาญที่มีความประณีต แม่นยำ และเปี่ยมด้วยความน่าเชื่อถือ มุ่งเน้นการจัดโครงสร้างข้อมูลบุคลากรอย่างชัดเจน เพื่อให้ผู้มาติดต่อค้นหาและเข้าถึงข้อมูลได้อย่างรวดเร็ว โดยไม่ถูกรบกวนด้วยองค์ประกอบที่ไม่จำเป็น

หัวใจหลักของงานภาพคือความสมดุลระหว่างพื้นหลังสีเข้มลุ่มลึก (Deep Cosmic Background) กับคอนเทนเนอร์การ์ดแก้วสีขาวสะอาดตา (Translucent White Glassmorphism) พร้อมรายละเอียดกราฟิกที่คมชัด เช่น เลนส์แว่นขยายค้นหาแบบ 3D และเส้นแสงชี้นำเมื่อนำเมาส์ไปชี้การ์ด

**Key Characteristics:**
- **Clarity over Noise:** ตัดทอนอิโมจิและองค์ประกอบรกรุงรัง ให้ความสำคัญกับชื่อ ตำแหน่ง และลิงก์ปลายทาง
- **Lifted & Dynamic Depth:** การ์ดยกตัวลอยอย่างเด่นชัดเมื่อโต้ตอบ (Hover Lift) พร้อมเงาสีครามละมุนตา
- **Dual-Script Precision:** จัดวางอักษรไทย (Prompt) ควบคู่กับละติน (Plus Jakarta Sans) อย่างลงตัว

## Colors

ชุดสีเน้นความคมชัดของข้อความสีเข้มบนพื้นหลังสีสว่าง ล้อมรอบด้วยพื้นหลังสีรัตติกาลและการไล่เฉดสีครามทรงพลัง

### Primary
- **Indigo Authority** (`#4f46e5`): สีหลักแสดงความเป็นมืออาชีพ ใช้สำหรับโฟกัสและแถบไฮไลท์
- **Electric Indigo** (`#6366f1`): สีเมื่อมีปฏิสัมพันธ์ (Hover state) ของปุ่มและเงาเรืองแสง

### Neutral
- **Midnight Deep** (`#0b1120`): สีพื้นหลังหน้าเว็บระดับล่างสุด สร้างบรรยากาศสุขุมนุ่มลึก
- **Slate Obsidian** (`#0f172a`): สีหัวข้อหลักและขอบเส้นที่มีความสำคัญสูง
- **Pure Canvas** (`#ffffff`): สีพื้นผิวของการ์ดข้อมูลสมาชิก ให้ความสว่างและอ่านง่ายสูงสุด
- **Subtle Ash** (`#64748b`): สีข้อความคำอธิบาย ลิงก์ และข้อมูลระดับรอง
- **Border Mist** (`#eef2f6`): สีเส้นขอบการ์ดเพื่อแบ่งขอบเขตอย่างนุ่มนวล

### Accents & Avatars
- **Emerald Pulse** (`#10b981`): แสดงสถานะความพร้อมและการออนไลน์
- **Verified Blue** (`#3b82f6`): ตราสัญลักษณ์ยืนยันความถูกต้องของโปรไฟล์
- **Avatar Tonal Gradients**: ชุดสีเกรเดียนท์เฉพาะตัวสำหรับตัวอักษรย่อของแต่ละบุคคล (Blue, Emerald, Purple, Orange, Rose, Teal, Indigo)

### Named Rules
**The Rarity of Glow Rule.** แสงเรืองแสงสีคราม (Primary Glow) จะปรากฏเฉพาะเมื่อเกิดการโต้ตอบกับผู้ใช้ (Focus ในช่องค้นหา หรือ Hover บนการ์ดสมาชิก) เท่านั้น เพื่อให้แสงทำหน้าที่ชี้นำสายตาอย่างแท้จริง

## Typography

**Display & Headline Font:** Prompt (ฟอนต์ไร้หัวสไตล์โมเดิร์นที่อ่านง่ายและเป็นทางการ)  
**Body & UI Font:** Prompt ผสมผสานกับ Plus Jakarta Sans สำหรับตัวเลข แท็ก และ URL  

**Character:** การจับคู่ฟอนต์เน้นความโปร่ง สบายตา และมีสัดส่วนเรขาคณิตที่สมดุล ให้ความรู้สึกทันสมัยและเป็นมิตร

### Hierarchy
- **Display** (Bold 700, 300px, Line-height 1.2): หัวข้อหลักของหน้าเว็บ (H1)
- **Title** (Semi-bold 600, 17px, Line-height 1.3): ชื่อ-นามสกุลของบุคลากร
- **Body** (Regular 400, 15px, Line-height 1.5): ข้อความแนะนำและคำอธิบายใต้หัวข้อ
- **Sub-label / URL** (Medium 500, 13px, Plus Jakarta Sans): ที่อยู่เว็บไซต์ย่อและสถิติจำนวน
- **Role Tag** (Semi-bold 600, 11px, Letter-spacing 0.02em): ป้ายกำกับตำแหน่ง/แผนก

## Layout

- **Spatial Container:** คอนเทนเนอร์หลักความกว้างไม่เกิน `680px` จัดกึ่งกลางหน้าจอ
- **Vertical Rhythm:** ระยะห่างระหว่างการ์ดสมาชิกสม่ำเสมอที่ `14px`
- **Responsive Padding:** บนเดสก์ท็อปใช้ Padding `40px 32px` และบนหน้าจอแคบ (≤540px) ปรับลงเป็น `28px 18px` เพื่อรักษาพื้นที่ใช้งาน

## Elevation & Depth

ระบบนี้ใช้มิติความลึกแบบ **Lifted & Dynamic** โดยแบ่งระดับชั้น (Layering) อย่างเด็ดขาด:

### Shadow Vocabulary
- **Backdrop Blur Elevation** (`box-shadow: 0 25px 60px -15px rgba(0, 0, 0, 0.35)`): คอนเทนเนอร์หลักลอยเด่นเหนือพื้นหลังพร้อมเอฟเฟกต์เบลอ 20px
- **Card Rest** (`box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03)`): การ์ดในสภาวะปกติแนบชิดกับพื้นผิวกล่องหลัก
- **Card Hover Lift** (`box-shadow: 0 16px 30px -8px rgba(99, 102, 241, 0.18)`): การ์ดลอยสูงขึ้น 3px พร้อมขยายขนาด 1.01 เท่า และเปล่งแสงสีครามรอบตัว
- **Search Glass 3D Depth** (`feDropShadow dx="0.6" dy="1.4" stdDeviation="0.9" rgba(15, 23, 42, 0.32)`): แว่นขยายมีมิติแสงเงาเสมือนกระจกนูนจริง

### Named Rules
**The Lift on Intent Rule.** องค์ประกอบจะลอยตัวและทอดเงาเข้มขึ้นเฉพาะเมื่อผู้ใช้แสดงเจตนาจะคลิก (Intent) เท่านั้น เพื่อสร้างสัมผัสแบบ Tactile Feedback

## Shapes

- **Contained Rounding:** กล่องหลักขอบมนใหญ่พิเศษ (`32px`) สื่อถึงความอ่อนโยนและปลอดภัย
- **Card Geometry:** การ์ดสมาชิกขอบมนมนพองาม (`20px`)
- **Action Elements:** ปุ่มแอ็กชันและช่องค้นหาใช้ความโค้งมนกระชับ (`14px` - `16px`)
- **Precision Dots:** ตราสัญลักษณ์ออนไลน์และ Verified Badge มีรูปทรงกลมมนสมบูรณ์ (`50%`)

## Components

### Member Card
- **Shape:** มน `20px`, ขอบเส้น `1.5px solid #eef2f6`
- **Interactions:** เมื่อ Hover ขอบด้านซ้ายจะปรากฏแถบสีเกรเดียนท์หนา `5px` พร้อมยกการ์ดลอยขึ้น
- **Internal Spacing:** `16px 20px`

### Search Box & 3D Glass Icon
- **Shape:** มน `16px`, พื้นหลัง `#f8fafc`
- **Search Icon:** แว่นขยาย Vector เลนส์แก้วสีฟ้าเงาวาว 3D พร้อมข้อต่อเงินและด้ามจับทรงกระบอก
- **Focus:** กรอบสีครามเข้ม `#6366f1` พร้อมวงแหวนแสงเงา `0 0 0 4px rgba(99, 102, 241, 0.15)`

### Open Action Button
- **Shape:** สี่เหลี่ยมขอบมน `14px`, ขนาด `40px × 40px`
- **Rest:** พื้นหลัง `#f8fafc` เส้นขอบ `#e2e8f0` และไอคอนลูกศรเฉียง
- **Hover:** เปลี่ยนเป็นสีม่วงครามสดใส `#6366f1` อักษรขาว พร้อมขยับเลื่อนไปทางขวา `4px`

### Role Tag
- **Style:** แถบสีเทาอ่อน `#f1f5f9` อักษรสีเทาเข้ม `#475569` ขอบมน `6px`

## Do's and Don'ts

### Do:
- **Do** ใช้ไอคอน Vector SVG ที่มีความคมชัดสูงแทนอิโมจิทั่วไป
- **Do** รักษาความเร็วในการตอบสนองของการค้นหาแบบ Real-time โดยไม่ให้มีอาการกระตุก
- **Do** ใช้แถบสีทางซ้ายของการ์ดเพื่อบ่งบอกสถานะการ Hover อย่างนุ่มนวล

### Don't:
- **Don't** ใส่อิโมจิในข้อความหรือป้ายสถานะเพื่อป้องกันไม่ให้กระทบต่อความเป็นทางการ
- **Don't** ใช้เงาสีดำทึบใต้การ์ด ให้ใช้เงาสีครามโปร่งแสง (Indigo Tinted Shadow) เสมอ
- **Don't** ปรับลดขนาดตัวอักษรชื่อบุคลากรให้เล็กกว่า 15px เพื่อให้อ่านได้อย่างชัดเจนบนมือถือ

