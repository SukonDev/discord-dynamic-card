# 🚀 discord-dynamic-card

[![npm version](https://img.shields.io/npm/v/discord-dynamic-card-rs.svg)](https://www.npmjs.com/package/discord-dynamic-card-rs)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://github.com/SukonDev/discord-dynamic-card/workflows/CI/badge.svg)](https://github.com/YOUR_USERNAME/discord-dynamic-card-rs/actions)

A blazing-fast, Rust-powered dynamic image generator for Node.js. Designed specifically for Discord Bots to render high-quality Roleplay character cards, Welcome banners, and Game HUDs in milliseconds.

## ✨ ทำไมต้องใช้ Library นี้? (Key Features)

- 🦀 **Blazing Fast:** Core engine เขียนด้วย Rust (`resvg` + `napi-rs`) เร็วกว่า Canvas หรือ Jimp ใน Node.js หลายเท่าตัว
- 🇹🇭 **Thai Font Support:** รองรับฟอนต์ภาษาไทยและสระลอยแบบ 100% โดยไม่ต้องติดตั้งฟอนต์ลงใน OS ของเซิร์ฟเวอร์
- 🎨 **SVG Templating:** ออกแบบหน้าตาการ์ดด้วย SVG ธรรมดา แล้วใช้ JSON โยนข้อมูล (เช่น ชื่อ, อาชีพ, จำนวนเงิน) เข้าไปสวมทับได้ทันที
- 💧 **Zero-Dependency (OS Level):** ไม่ต้องพึ่งพา `Cairo`, `Pango`, หรืคอเรื่องมือระดับ OS อื่นๆ ที่มักจะทำให้เกิดปัญหาตอน Deploy ขึ้น VPS
- 🛡️ **TypeScript Ready:** มี Type Definition ครบถ้วน รองรับ Auto-complete ใน VS Code

## 📦 Installation

```bash
npm install discord-dynamic-card
# หรือ
yarn add discord-dynamic-card
