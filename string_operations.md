# বেসিক স্ট্রিংস অপারেশনস 

### ক্যারেকটার এক্সেস 

পাইথনে অামরা একটা স্ট্রিং এর ভিতরের ক্যারেকটার গুলে কে []  সিনটেক্স দিয়ে এক্সেস করতে পারি ।  অন্যান্য প্রোগ্রামিং ল্যাংগুয়েজের মত পাইথনও জিরো বেসড ইনডেক্স ব্যবহার করে।  ধরি অামাদের একটা স্ট্রিং অাছে 

```python 
my_string = "Hello Python"
print my_string[2]
```
এখন বলুনতো অামদের এই কোডব্লকসটুকুর অাউটপুট কি হবে? ঠিক ধরেছেন, অাউটপুট হবে ‍`l`।  অাচ্ছা এইবার বলুনতো  `my_string[6]` এটা প্রিন্ট করলে অাউটপুট কি হবে?  হিন্টস : টার্মিনাল ওপেন করে চেক করে দেখুন । 

### স্ট্রিং লেন্থ । 

স্ট্রিং লেন্থ বের করা পাইথনে খুব সহজ।  অামরা যদি my_string স্ট্রিংটির লেন্থ বের করতে চাই তাহলে নিচের মত লিখবেন। 

```python 
print len(my_string)
```

এই len() ফাংশনটি স্ট্রিং লেন্থ বের করার জন্য ব্যবহার করা হয়। এটি পাইথন লিস্টের লেন্থ বের করার জন্যও ব্যবহার করা হয়। লিস্ট চ্যাপ্টারে অারও বিস্তারিত অালোচনা করব। 

### মল্টিলাইন স্ট্রিং ।

এতক্ষন অামরা স্ট্রিং হিসেবে একটি করে লাইন ব্যবহার করছি।  কিন্তু ধরুন অাপনার মনে হল স্ট্রিং হিসেবে অাপনি গরুর বা হাতির রচনা লিখবেন । তাহলে অামরা নিচের মত করে লিখতে পারি। 

```python 
rochona = """The cow is a domestic animal. It has four legs and a long tail and 
We have a cow."""

print rochona
```

### বড় হাতের এবং ছোট হাতের লেখা।

```python
big = "AAA"
print big.lower()

small = "aaa"
print small.upper()
```
str.lower() দিয়ে বড় হাতের লেখাকে ছোট হাতের এবং str.upper() দিয়ে ছোট হাতের লেখাকে বড় হাতের লেখায় রুপন্তরিত করা যাবে। 


