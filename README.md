<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0a0a0a,1a1a1a,0a0a0a&height=20&section=header" width="100%"/>

```
██╗  ██╗ █████╗ ███╗   ███╗    ███████╗███╗   ██╗███████╗ █████╗ ██╗  ██╗███████╗██████╗ ███████╗
██║ ██╔╝██╔══██╗████╗ ████║    ██╔════╝████╗  ██║██╔════╝██╔══██╗██║ ██╔╝██╔════╝██╔══██╗██╔════╝
█████╔╝ ███████║██╔████╔██║    ███████╗██╔██╗ ██║█████╗  ███████║█████╔╝ █████╗  ██████╔╝███████╗
██╔═██╗ ██╔══██║██║╚██╔╝██║    ╚════██║██║╚██╗██║██╔══╝  ██╔══██║██╔═██╗ ██╔══╝  ██╔══██╗╚════██║
██║  ██╗██║  ██║██║ ╚═╝ ██║    ███████║██║ ╚████║███████╗██║  ██║██║  ██╗███████╗██║  ██║███████║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝    ╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0a0a0a,1a1a1a,0a0a0a&height=20&section=header" width="100%"/>

<br/>

<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=900&q=90&fit=crop" width="55%" style="border-radius:0px; filter: contrast(1.1)"/>

<br/>

```
             ╔══════════════════════════════════════════╗
             ║   WHERE EVERY STEP IS A STATEMENT. ™    ║
             ╚══════════════════════════════════════════╝
```

<br/>

![Store](https://img.shields.io/badge/KamSneakers-Premium%20Store-CC0000?style=for-the-badge&labelColor=0a0a0a)
&nbsp;
![Stack](https://img.shields.io/badge/HTML%20·%20CSS%20·%20JS-Built%20From%20Scratch-1a1a1a?style=for-the-badge&labelColor=CC0000)
&nbsp;
![Status](https://img.shields.io/badge/Status-Live%20%26%20Selling-CC0000?style=for-the-badge&labelColor=0a0a0a)

<br/>

</div>

---

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ◈  THE STORE  ◈  THE STACK  ◈  THE SETUP  ◈  THE API  ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

---

## ◈ THE STORE

**KamSneakers** is a luxury sneaker e-commerce experience — built with zero frameworks, pure craftsmanship, raw HTML, CSS and JavaScript. Every detail is intentional. Every pixel is deliberate.

This isn't just a shop. It's a destination for people who take their footwear seriously.

> *Curated drops. Premium pairs. No compromises.*

---

## ◈ FEATURES

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                   │
│   🖤  Premium product grid with hover reveals                     │
│   🔴  Dynamic size selection & stock indicators                   │
│   🖤  Smooth cart system with quantity control                    │
│   🔴  Secure checkout powered by Paystack                        │
│   🖤  Curated collections — Runners · Classics · Collabs         │
│   🔴  Search & filter by brand, size, price                      │
│   🖤  Product detail pages with full image gallery               │
│   🔴  Order confirmation & receipt flow                          │
│   🖤  Fully responsive — desktop to mobile                       │
│   🔴  Zero dependencies — pure vanilla code                      │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

---

## ◈ PROJECT STRUCTURE

```
👟 kamsneakers/
│
├── 📄 index.html          ← Landing page & hero
├── 📄 shop.html           ← Full product catalogue
├── 📄 product.html        ← Single product detail page
├── 📄 cart.html           ← Cart & checkout flow
├── 📄 README.md           ← You are here.
└── 📄 LICENSE             ← MIT
```

---

## ◈ DEPLOY TO GITHUB PAGES

**— Step 01 · Create Your Repository**

```
① Go to github.com → sign in
② Click  +  →  New Repository
③ Name it:  kamsneakers
④ Visibility: Public
⑤ Check "Add a README file"
⑥ Hit  Create repository
```

**— Step 02 · Upload Your Files**

```bash
# Via Git CLI:
git clone https://github.com/YOUR_USERNAME/kamsneakers.git
cd kamsneakers

git add .
git commit -m "🖤 KamSneakers — launch"
git push origin main
```

```
# Via Drag & Drop:
① Open repo on GitHub
② Add file → Upload files
③ Drag in all your project files
④ Commit message:  🖤 Initial drop
⑤ Commit changes
```

**— Step 03 · Go Live**

```
① Repo → Settings → Pages
② Source: Deploy from a branch
③ Branch: main  |  Folder: / (root)
④ Save — wait 60 seconds
⑤ Your store is live at:

   https://YOUR_USERNAME.github.io/kamsneakers
```

---

## ◈ PAYMENT SETUP (PAYSTACK)

**— Step 01 · Create Account**
```
→ dashboard.paystack.com
→ Sign up with business email
→ Complete KYC (BVN + valid ID)
```

**— Step 02 · Get Your Key**
```
Dashboard → Settings → API Keys & Webhooks
Copy:  pk_live_...   (live)
  or:  pk_test_...   (testing)
```

**— Step 03 · Add It to Your Code**

```javascript
// In index.html or cart.html — find this line:
const PAYSTACK_KEY = 'pk_test_xxxxxxxxxxxxxxxxxxxxxxxx';

// Replace with your real key:
const PAYSTACK_KEY = 'pk_live_yourrealkeyhere';
```

**— Step 04 · Link Your Bank**
```
Dashboard → Settings → Bank Account → Add Account
Select your bank → Enter account number
Paystack verifies → payments auto-settle daily ✓
```

> 🔐 Rule #1 — **Never** expose your **Secret Key** in frontend code. Public Key only.

---

## ◈ API KEYS REFERENCE

| Service | Where to Get It | Where It Goes |
|---|---|---|
| **Paystack Public Key** | [dashboard.paystack.com](https://dashboard.paystack.com) | `cart.html` or `index.html` |
| **Unsplash Access Key** | [unsplash.com/developers](https://unsplash.com/developers) | `shop.html` (if used) |

---

## ◈ COLOUR PALETTE

```
┌──────────────────────────────────────────────────────────┐
│                                                            │
│   ██████  #0A0A0A  —  Void Black    Primary background    │
│   ██████  #1A1A1A  —  Charcoal      Cards, surfaces       │
│   ██████  #CC0000  —  Blood Red     CTAs, accents, fire   │
│   ██████  #8B0000  —  Deep Red      Hover states          │
│   ██████  #2B2B2B  —  Dark Grey     Borders, dividers     │
│   ██████  #9A9A9A  —  Silver        Muted text, labels    │
│   ██████  #FFFFFF  —  White         Headlines, contrast   │
│                                                            │
└──────────────────────────────────────────────────────────┘
```

---

## ◈ TECH STACK

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-0a0a0a?style=for-the-badge&logo=html5&logoColor=CC0000)
&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-1a1a1a?style=for-the-badge&logo=css3&logoColor=CC0000)
&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0a?style=for-the-badge&logo=javascript&logoColor=CC0000)
&nbsp;
![Paystack](https://img.shields.io/badge/Paystack-CC0000?style=for-the-badge&logoColor=white)
&nbsp;
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-1a1a1a?style=for-the-badge&logo=github&logoColor=white)
&nbsp;
![Zero Deps](https://img.shields.io/badge/Dependencies-0%20👟-CC0000?style=for-the-badge)

</div>

<br/>

| Layer | Technology |
|---|---|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Fonts** | Custom premium typography (Google Fonts) |
| **Payments** | Paystack Inline JS |
| **Hosting** | GitHub Pages / Netlify |
| **Build Tools** | None — zero dependencies |
| **Images** | Unsplash API or custom product shots |

---

## ◈ REPO SETUP CHECKLIST

```
  Before you go live, run through this:
```

- [ ] Repository named `kamsneakers`
- [ ] Description set in About section
- [ ] Live URL added to repo profile
- [ ] Topics added — `sneakers` `ecommerce` `html` `css` `javascript` `paystack` `streetwear` `nigeria`
- [ ] GitHub Pages enabled in Settings → Pages
- [ ] Paystack public key replaced in code
- [ ] Bank account linked in Paystack dashboard
- [ ] All product images loading correctly
- [ ] Cart & checkout tested end-to-end
- [ ] Mobile responsiveness confirmed

---

## ◈ LICENSE

```
MIT License  ©  2025  KamSneakers

Free to use. Free to modify. Free to distribute.
Just don't remove the credits. Respect the craft.
```

---

## ◈ SUPPORT

Open an **Issue** on this repo. Include the step you're on, the error you're seeing, and your browser. We'll sort it.

---

<div align="center">

<br/>

```
  ┌───────────────────────────────────────────────┐
  │                                               │
  │   👟  KamSneakers  —  Est. 2025               │
  │   Where Every Step Is A Statement.™           │
  │                                               │
  └───────────────────────────────────────────────┘
```

![Footer](https://img.shields.io/badge/Built%20Different-KamSneakers%20👟-CC0000?style=for-the-badge&labelColor=0a0a0a)

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=CC0000,8B0000,0a0a0a&height=8&section=footer" width="100%"/>

</div>
