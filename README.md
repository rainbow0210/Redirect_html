# Redirect_html

# Japanese
## 概要

指定されたURLへブラウザを自動的にリダイレクトするシンプルなHTMLツールです。ページ読み込み後、設定したURLに自動的に遷移します。

## 使用技術

- 言語: HTML、JavaScript
- 用途: ブラウザベースのリダイレクト機能

## 使い方

### 前提条件

ブラウザ（Chrome、Firefox、Safari、Edge等）があれば動作します。

### インストール方法

```bash
git clone https://github.com/rainbow0210/Redirect_html.git
cd Redirect_html
```

### 基本的な使い方

1. `Redirect.html`ファイルをテキストエディタで開いてください
2. ファイル内の `your_setting_link` をリダイレクト先のURLに置き換えてください
3. ファイルを保存し、ブラウザで開いてください
4. ページがロードされると、設定したURLへ自動的にリダイレクトされます

## 主な機能

- 自動URL リダイレクト：ページ読み込み後、指定URLへ自動遷移
- シンプルなUI：リダイレクト中であることを表示
- 軽量：外部依存なし、単一HTMLファイル

## 設定

### リダイレクト先URLの設定

`Redirect.html`内の以下の行を編集してください：

```javascript
document.location.href = "your_setting_link";
```

`your_setting_link` の部分を、実際のリダイレクト先URL（例：`https://example.com`）に置き換えてください。

## ライセンス

Unlicense license

# English
# Redirect_html

## Overview

A simple HTML tool that automatically redirects the browser to a specified URL. After the page loads, it automatically navigates to the configured URL.

## Technology Stack

- Language: HTML, JavaScript
- Purpose: Browser-based redirection functionality

## Usage

### Prerequisites

browser (Chrome, Firefox, Safari, Edge, etc.) is required.

### Installation

```bash
git clone https://github.com/rainbow0210/Redirect_html.git
cd Redirect_html
```

### Basic Usage

1. Open the `Redirect.html` file with a text editor
2. Replace `your_setting_link` with your target redirection URL
3. Save the file and open it in a browser
4. The page will automatically redirect to the configured URL upon loading

## Main Features

- Automatic URL Redirection: Automatically navigates to the specified URL upon page load
- Simple UI: Displays a message indicating that redirection is in progress
- Lightweight: No external dependencies, single HTML file

## Configuration

### Setting the Redirection URL

Edit the following line in `Redirect.html`:

```javascript
document.location.href = "your_setting_link";
```

Replace `your_setting_link` with your actual target URL (e.g., `https://example.com`).

## License

Unlicense license
