# flutter_app_bar

## Getting Started

### 1.AppBar Properties:
a. title:
- title প্রপার্টি ব্যবহার করে AppBar-এ টাইটেল সেট করা হয়। এটি সাধারণত একটি Text widget হয়, তবে যেকোনো widget হতে পারে।
b. actions:
  - actions প্রপার্টি ব্যবহার করে AppBar-এ একশন বাটন যোগ করা যায়। এটি একটি List<Widget> নেয়।
c. leading:
   - leading প্রপার্টি ব্যবহার করে AppBar-এর বাম পাশে একটি widget যোগ করা যায়। সাধারণত এটি একটি ব্যাক বাটন বা ড্রয়ার আইকন হয়।
d. backgroundColor: 
   - backgroundColor প্রপার্টি ব্যবহার করে AppBar-এর ব্যাকগ্রাউন্ড কালার সেট করা যায়।
e. elevation:
   - elevation প্রপার্টি ব্যবহার করে AppBar-এর শ্যাডো ডেপথ সেট করা যায়। এটি একটি double মান নেয়।
f. brightness:
   - brightness প্রপার্টি ব্যবহার করে AppBar-এর টেক্সট এবং আইকনের কালার সেট করা যায়। এটি Brightness.light বা Brightness.dark হতে পারে।
g. centerTitle:
   - centerTitle প্রপার্টি ব্যবহার করে টাইটেলকে AppBar-এর মাঝখানে সেন্টার করা যায়। এটি একটি bool মান নেয়। 
h. flexibleSpace:
    - flexibleSpace প্রপার্টি ব্যবহার করে AppBar-এর পিছনে একটি flexible space যোগ করা যায়। এটি সাধারণত একটি Container বা Image widget হয়। 
i. bottom:
  - bottom প্রপার্টি ব্যবহার করে AppBar-এর নিচে একটি widget যোগ করা যায়। এটি সাধারণত একটি TabBar বা PreferredSize widget হয়।
### 2.AppBar with SliverAppBar:
  - SliverAppBar ব্যবহার করে আপনি একটি কাস্টম স্ক্রলিং AppBar তৈরি করতে পারেন। এটি সাধারণত CustomScrollView এর সাথে ব্যবহার করা হয়।
### 3. AppBar with Theme:
   - Theme ব্যবহার করে আপনি AppBar-এর স্টাইল গ্লোবালি কাস্টমাইজ করতে পারেন।
### 4.AppBar with Back Button:
   - যদি আপনি একটি ব্যাক বাটন যোগ করতে চান, তাহলে automaticallyImplyLeading প্রপার্টি ব্যবহার করতে পারেন।
### 4. AppBar with Transparent Background:
  - একটি ট্রান্সপারেন্ট AppBar তৈরি করতে backgroundColor প্রপার্টি ব্যবহার করুন।
### 5. AppBar with Gradient Background:
   - একটি গ্রেডিয়েন্ট ব্যাকগ্রাউন্ড সহ AppBar তৈরি করতে flexibleSpace প্রপার্টি ব্যবহার করুন।
### 6. AppBar with Custom Height:
   - একটি কাস্টম উচ্চতা সহ AppBar তৈরি করতে PreferredSize widget ব্যবহার করুন।
### 7. AppBar with Search:
   - একটি সার্চ ফাংশনালিটি সহ AppBar তৈরি করতে TextField ব্যবহার করুন।
### 8.AppBar with Bottom TabBar:
   - একটি TabBar সহ AppBar তৈরি করতে bottom প্রপার্টি ব্যবহার করুন।
### 9. AppBar with Drawer:
  - একটি ড্রয়ার সহ AppBar তৈরি করতে Scaffold widget ব্যবহার করুন।
### 10. AppBar with Overflow Menu:
   - একটি ওভারফ্লো মেনু সহ AppBar তৈরি করতে PopupMenuButton ব্যবহার করুন।

### 11. AppBar with Custom Text Style:
   - একটি কাস্টম টেক্সট স্টাইল সহ AppBar তৈরি করতে TextStyle ব্যবহার করুন।
### 12.AppBar with Custom Shape:
   - একটি কাস্টম শেপ সহ AppBar তৈরি করতে shape প্রপার্টি ব্যবহার করুন।

### 13.AppBar with Custom Shadow:
  - একটি কাস্টম শ্যাডো সহ AppBar তৈরি করতে elevation প্রপার্টি ব্যবহার করুন।
### 14.AppBar with Custom Bottom Widget:
  - একটি কাস্টম বটম widget সহ AppBar তৈরি করতে bottom প্রপার্টি ব্যবহার করুন।
### 15.AppBar with Custom Action Widget:
  - একটি কাস্টম একশন widget সহ AppBar তৈরি করতে actions প্রপার্টি ব্যবহার করুন।
### 16. AppBar with Custom Leading Widget:
  - একটি কাস্টম লিডিং widget সহ AppBar তৈরি করতে leading প্রপার্টি ব্যবহার করুন।
### 17.AppBar with Custom Text Color:
  - একটি কাস্টম টেক্সট কালার সহ AppBar তৈরি করতে textTheme প্রপার্টি ব্যবহার করুন।
### 18. AppBar with Custom Background  Color:
  - একটি কাস্টম টেক্সট কালার সহ AppBar তৈরি করতে backgroundColor প্রপার্টি ব্যবহার করুন।
### 19. AppBar with Custom Icon Color:
  - একটি কাস্টম আইকন কালার সহ AppBar তৈরি করতে iconTheme প্রপার্টি ব্যবহার করুন।
### 20.AppBar with Custom Action Widget and Icon:
  - একটি কাস্টম একশন widget এবং আইকন সহ AppBar তৈরি করতে actions প্রপার্টি ব্যবহার করুন।
### 21.AppBar with Custom Bottom Height:
  - একটি কাস্টম বটম উচ্চতা সহ AppBar তৈরি করতে bottom প্রপার্টি ব্যবহার করুন।
### 22.AppBar with Custom Toolbar Height:
  - একটি কাস্টম টুলবার উচ্চতা সহ AppBar তৈরি করতে toolbarHeight প্রপার্টি ব্যবহার করুন।
### 23. AppBar with Custom Title Spacing:
  - একটি কাস্টম টাইটেল স্পেসিং সহ AppBar তৈরি করতে titleSpacing প্রপার্টি ব্যবহার করুন।