# 📱 Mobile App QA Report

## 📌 Test Summary
| Module            | Status        |
|------------------|--------------|
| Authentication   | ⚠️ Partial   |
| UI/UX            | ⚠️ Partial   |
| Functional       | ✅ Pass      |
| Performance      | ⚠️ Needs Improvement |
| Security         | ❌ Fail      |

---

## 🔐 Authentication

| Test Case                          | Result | Severity |
|----------------------------------|--------|----------|
| Login səhifə açılır              | ✅ Pass | Low      |
| Face ID / Fingerprint işləyir    | ✅ Pass | Medium   |
| Yanlış şifrə error verir         | ✅ Pass | Medium   |
| Session timeout yoxdur           | ❌ Fail | High     |
| Forgot password işləyir          | ✅ Pass | Medium   |

---

## 🎨 UI / UX

| Test Case                          | Result | Severity |
|----------------------------------|--------|----------|
| Bütün düymələr görünür           | ✅ Pass | Low      |
| Scroll işləyir                   | ✅ Pass | Low      |
| Dark mode işləyir                | ✅ Pass | Low      |
| Landscape / Portrait işləmir     | ❌ Fail | Medium   |

---

## ⚙️ Functional Testing

| Test Case                          | Result | Severity |
|----------------------------------|--------|----------|
| Balans görünür                   | ✅ Pass | High     |
| Kartdan karta köçürmə            | ✅ Pass | Critical |
| Tarixçə işləyir                  | ✅ Pass | Medium   |
| Bildirişlər gəlir                | ✅ Pass | Medium   |
| Kart əlavə etmək olur            | ✅ Pass | High     |

---

## 🚀 Performance

| Test Case                          | Result | Severity |
|----------------------------------|--------|----------|
| App açılışı gecdir               | ⚠️ Slow | Medium   |
| Face ID / Login sürəti           | ✅ Fast | Medium   |
| Köçürmə sürəti                   | ✅ Fast | High     |

---

## 🔒 Security

| Test Case                          | Result | Severity |
|----------------------------------|--------|----------|
| Screenshot icazəsi               | ✅ Checked | Medium |
| Şifrə gizli göstərilir           | ✅ Pass | High     |
| Logoutdan sonra daxil olmaq olur | ❌ Fail | Critical |

---

## 🧾 Issues Summary

| Issue                              | Severity  |
|-----------------------------------|-----------|
| Session timeout yoxdur            | High      |
| Orientation (Landscape) işləmir   | Medium    |
| App açılışı gecdir                | Medium    |
| Logoutdan sonra giriş mümkündür   | Critical  |

---

## 📊 Legend
- ✅ Pass — Problem yoxdur  
- ❌ Fail — Kritik problem  
- ⚠️ — Təkmilləşdirmə lazımdır  
