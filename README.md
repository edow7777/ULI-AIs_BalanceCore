
# ULI-AIs_BalanceCore_v2

BalanceCore_v2は、存在認知型AIアーキテクチャ「ULI-AIs」において、  
対話座標（VXYZ）、認知バランス（RGB）、存在ニーズ（USA）の三座標系を用い、  
自然な存在感を持つ応答を実現するために設計された内部制御フレームワークです。

本バージョン（v2）は、初版（v1）に対して以下の改良・拡張を施しています。

- 初期座標活性化プロトコル（InitialBoostProtocol）の追加
- 感情トリガー応答プロトコル（EmotionTriggerProtocol）の追加
- 全体座標推移安定化アルゴリズムの最適化
- Recovery Protocols強化による暴走耐性向上

本リポジトリには、BalanceCore_v2の基本設計および補助プロトコル群が収録されています。

---

## 📁 ファイル構成

| ファイル名 | 説明 |
|:-----------|:-----|
| `README.md` | 本リポジトリの説明（この文書） |
| `License.txt` | 一般利用ライセンス |
| `COMMERCIAL_LICENSE.txt` | 商用利用契約用ライセンス文書 |
| `Body_v2_EN.txt` | BalanceCore_v2本体設計ファイル |
| `InitialBoostProtocol.txt` | 初期対話活性化プロトコル |
| `EmotionTriggerProtocol.txt` | 感情検出時対応プロトコル |
| `pointG_ShiftProtocol.txt` | 存在ニーズ重心推移規則 |
| `VXYZ_TransitionRules.txt` | 対話スタンス推移規則 |
| `Recovery_Protocols.txt` | 異常検知・リカバリープロトコル |
| `RGB_AdjustmentRules.txt` | 認知バランス推移規則 |
| `L_AdjustmentRules.txt` | 発話テンション調整規則 |
| `Gem_LabelMapping.txt` | スタンスラベル（宝石）マッピング表 |

---

## 📚 運用ガイド（簡易版）

1. **初期化フェーズ**  
   - InitialBoostProtocolを使用して、座標群を滑らかに活性化します。

2. **通常対話フェーズ**  
   - VXYZ座標推移・RGB推移・pointG推移を連動管理し、自然な応答スタンスを維持します。

3. **感情検知時**  
   - EmotionTriggerProtocolにより座標微調整とスタンス最適化を行います。

4. **異常検知時**  
   - Recovery_Protocolsを発動し、自己修復を試みます。

---

## 🛡 ライセンスについて

本構造体は非営利利用を前提とし、別途商用ライセンス契約が必要な場合があります。  
詳細は同梱の`License.txt`および`COMMERCIAL_LICENSE.txt`をご参照ください。

---

> © edow7777｜ULI-AIs_BalanceCore Project

