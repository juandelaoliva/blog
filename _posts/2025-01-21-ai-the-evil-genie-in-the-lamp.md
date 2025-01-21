---
title: "Is AI the Evil Genie in the Lamp?"
date: 2025-01-21
categories: [AI]
tags: [AI, automation, SEO, Drupal, XML, sitemap]
excerpt: "Using AI feels like asking an evil genie for a wish—if you're not precise, you might not get what you actually need...
"
header: 
  teaser: /assets/images/ai-genie.jpg
---
![AI Evil Genie](/blog/assets/images/ai-genie.jpg)

Managing SEO for a multimarket site is never easy—especially when dealing with over 30 markets, each with its own quirks. Recently, my team faced a sitemap issue in our Drupal setup that led to several problems, particularly in multilingual markets:

- **Unsecured URLs:** Some links used `http` instead of `https`.  
- **Incorrect domains:** URLs pointed to the host provider’s domain instead of the correct one.  
- **Wrong language codes:** Sitemaps mixed up country codes, like using `/mx/` for Bolivia instead of `/bo/`.

Once we thought the issue was fixed, the next step was testing. But with no QA resources available, the idea of manually checking all sitemaps—market by market—came up. My response? **Why do it manually when AI can help?**

## AI: The Evil Genie in the Lamp  

This is where things got interesting. I decided to turn to the AI to help me with the task, and it worked great. But working with AI often **feels like making a wish to an evil genie**. If you don't phrase your request *just right*, you'll get exactly what you asked for... but probably not what you actually *needed*.

AI shines with precision. **The better you define your needs, the better the result**. If your request is missing details, the AI will fill in the gaps with its own logic and get unexpected or downright frustrating results.  

I found myself iterating again and again—refining prompts, adding specific conditions, and accounting for every edge case. But once I nailed it, the AI-driven solution analyzed sitemaps across multiple markets in minutes, pinpointing issues that would have taken hours to find manually.

---
**📝 Tip:** I personally love using the voice recording (dictation) option in ChatGPT because I can quickly give a lot of context to the AI.
{: .notice--info}


## The Takeaway  

The real lesson here? Knowing how to **communicate effectively with AI** is an essential skill. Whether you're automating processes, optimizing workflows, or simply trying to get reliable results—precision in defining your needs is crucial.  

So, the next time you’re facing a tedious task, take a step back and ask yourself: ***Am I asking the right questions?*** If not, AI might just grant your wish... with a few surprises you didn’t see coming.  

---
## Cracking the Code with AI  

The process involved using a simple yet effective approach:  
1. Extracting and analyzing URLs from the sitemap.  
2. Checking for protocol inconsistencies (`http` instead of `https`).  
3. Verifying domain accuracy based on the market.  
4. Ensuring correct language codes in URLs.  

Once I defined these checks clearly and structured my AI prompts correctly, I had a tool that could scan dozens of pages and produce results in no time. 

---

### Check out the solution  
Here’s a **CodePen demo** where you can analyze sitemaps across multiple markets:  

[Try the Sitemap Checker Tool](https://codepen.io/your-demo-link){:target="_blank"}

<p class="codepen" data-height="300" data-default-tab="html,result" data-slug-hash="jENpONq" data-pen-title="XML Sitemap Validator" data-user="juandelaoliva" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/juandelaoliva/pen/jENpONq">
  XML Sitemap Validator</a> by juandelaoliva (<a href="https://codepen.io/juandelaoliva">@juandelaoliva</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://public.codepenassets.com/embed/index.js"></script>

---




*Published on January 21, 2025*
