# 🚀 Competitive Programming Template

A powerful and customizable C++ template designed to speed up your coding during contests. It includes frequently used macros, fast I/O, debugging utilities, common algorithms, and a clean structure to help you focus on solving problems, not rewriting boilerplate.

## 📁 Features

- ✅ Fast Input/Output
- ✅ Short macros for data types, loops, and pairs
- ✅ Debug utilities (toggleable with `#define DEBUG`)
- ✅ Common STL includes
- ✅ Modular code for reuse
- ✅ Ready for Codeforces, AtCoder, and other platforms

---

## 📌 Template Preview

```cpp
#include <bits/stdc++.h>
using namespace std;

#define int long long
#define pb push_back
#define all(v) v.begin(), v.end()
#define endl '\n'
#define yes cout << "YES\n"
#define no cout << "NO\n"
#define fi first
#define se second

void solve() {
    // Your solution here
}

int32_t main() {
    ios::sync_with_stdio(false);
    cin.tie(nullptr);
    
    int t = 1;
    // cin >> t;
    while(t--) {
        solve();
    }

    return 0;
}
