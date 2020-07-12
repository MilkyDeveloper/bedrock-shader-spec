# 🇧​🇪​🇩​🇷​🇴​🇨​🇰​ 🇸​🇭​🇦​🇩​🇪​🇷​ 🇸​🇵​🇪​🇨​

<sub><sup>Please, feel free to use this guideline anywhere for your shaders. It's licensed over the unlicense meaning you can do anything with it.<br>Made by MilkyDeveloper and other contributors<br> Version 1<br>Made at an attempt to unify the shader community</sup></sub>

<details close>
<summary>🤷‍♀️ What is it?</summary>
Well, for me it's something like a <i>quality standard</i>. If my shaders don't meet the requirements I wont redistribute them or endorse them. For others, it may mean that the shaders have good performance, less bugs, a better QA, or you can freely edit them, for those looking to.
</details>

<details close>
<summary>🤨 For who?</summary>
Me and whoever else in the 🌐 wants flexible and stable shader to use, modify, and make. All my shaders will follow the guidelines. If your doing so, please let me know so in the issues tab.
</details>

<details close>
<summary>🆒 but why?</summary>
I constantly see rifts and complaints in the Bedrock Shader community. There's three types of people. The left are people who are outright ignorant to the idea of <i>modifications</i> and <i>adaptations</i>. The middle ones either are users who don't care or people that believe modifications are fine with appropriate credit. The right are people who endorse modifications that are made without credit. This specification intends to make everyone believe that shaders are pieces of code that can be used, modified, and moderated with appropriate guidelines.
</details>

## 1.0 Lɪᴄᴇɴsɪɴɢ
Of course this is up to the shader creator. But it would be awesome if you would make it an MIT License. Otherwise, if you want a more limited version, GPL v3 is fine. If you want to use something else, you can use a custom license, like [The ESBE Shader by @Mcbe_Eringi](https://mcpedl.com/esbe-2g/). Of course you don't have to provide an open-source license but it highly contributes to the community if you do so.

### 1.1 Cᴏᴅᴇ Tʜɪᴇᴠᴇs ᴀɴᴅ ʜᴏᴡ ᴛᴏ ᴅᴇᴀʟ ᴡɪᴛʜ ᴛʜᴇᴍ
**PLEASE** don't go all out on someone who is just learning how to code and forgot some licensing stuff. It's how I started.

Most *"code thieves"* are just kids who want to code something. It would be awesome if you would let them, assuming they gave credit and followed their license. Otherwise, you can list on your page who they are and what wrong thing they did. Eventually the shaders will fade away.

If they outright sold the shader and/or claimed they completely made it themselves, well, adios. I can't help you with that. If anyone of them are reading this, please, your upsetting the bedrock community full of kids and people wanting to change the world in their way. Profiting off of this is morally flawed.

## 2.0 Fɪʟᴇ Sᴛʀᴜᴄᴛᴜʀᴇ
File structuring is your choice. 

1. You can either not use materials and use the default naming scheme, but you can't use material files to specify features in use for `#infdef` furtherly not allowing you to use subpacks (the gui slider in the resource pack settings) and mipmaps along with others. For most simple shaders this is fine.

2. You can use materials to specify an `#infdef` and use subpacks for it. You can also use custom mipmaps and use other features. The disadvantage is if another shader doesn't have a material file then a shaderpack applied below will still run like it's at the top. In addition they may make it more confusing for someone to edit.  Many simple(r) shaders that have a lot of features, but still good performance, use this.

3. In my ideology, this one is the cream of the crop. A custom file structure. You can use materials to specify custom file locations. Personally, I use:

|          terrain         |            sky           |   other  | README.txt         | LICENSE.txt      |
|:------------------------:|:------------------------:|:--------:|--------------------|------------------|
| renderchunk              | skytexture               | entity   | How to Edit        | MIT              |
| color_texture            | cubemap                  | banner   | Credits            | GPL              |
| rain                     | clouds                   | lighting | Performance/GFlops | AGPL             |
| water code snippets      | noise                    | particle | Shaderlabs         | Creative Commons |
| shadow snippets          | sun_moon/sunflare        | beacon   | Effort Given       | Custom License   |
| ASSETS FOR CODE SNIPPETS | ASSETS FOR CODE SNIPPETS | ?        |                    |                  |

It would be awesome if bedrock shaders would follow one in the three structures for ease of use and editing for end-users, novice or experienced.



### 2.1 Sʜᴀᴅᴇʀ Sᴛʀᴜᴄᴛᴜʀᴇ
This section isn't about file structure. It's about how you arrange an `infdef`, `void main()`, and includes. The default shader structure is the best but you may have to rearrange the diffuse, so, it's best to stick how much you can to the default. However, for the end user, it may be much better and easier to include a `.fxh` or a `.h`, whether it be options, code, or anything in the middle. Be sure to make a `float` that isn't being edited and change it to a `const` for better performance. You should usfooe coments like `//` to indicate what section your on or what a variable means. Respectively, something like `// Sunflare code from Shader Toy named X` or `// SNFI means Sun Flare Instensity. You can use snfi.a to specify the transparency and multiply snfi for color intensity.`

## 3.0 Eɴᴅ Usᴇʀ Usᴀʙɪʟɪᴛʏ
Remember the main audience of Minecraft, specifically bedrock. Shaders should be super simple to use and should have a subpack slider (if possible) to fix lag for users. You can't directly use shader files in subpacks but you can use material definitions (remember my favorite `infdef`?). It's also best not to bloat the UI with a custom Minecraft Logo or anything that users don't appreciate, unless they choose it with the subpack. Also if you want the shaders to bring more publicity remember to publish it on apps like MCPE Master and Addons for MCPE. If using an external website for downloads and news, be sure to make it short to the point. Making sites with Github Pages instead of Wix or Weebly is much better, if possible. The mistake I made was my website was too "elite" and it took some time to navigate the site to get to the downloads. If using an external link shortener, be sure to give steps on how to skip the ads.

### Everything else
🎉 If you want to add anything, please do. Anyways, enjoy some food: 

# 🍔🍕🍖🍗🍚🍜🍝🍞🍟🍠🍣🍤🍩🍪🍰🍴🍅🍇🍈🍉🍊🍌🍍🍒🍓🍲🥐🥑🥒🥓🥔🥕🥖🥗🥘🥙
