<div align="center">

  ## Discord Snippets by HerraHabibi

</div>

### Script Snippets

#### Quest Completer

This completes your Discord quests automatically without having to play the game, watch the video or stream the game. This script is based on the [Complete Discord Quest script by aamiaa repository](https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb).

- English version

  ```js
  eval(await(await fetch("https://raw.githubusercontent.com/HerraHabibi/discord-snippets/main/src/Quest-Completer-EN.js")).text());
  ```

- Spanish version

  ```js
  eval(await(await fetch("https://raw.githubusercontent.com/HerraHabibi/discord-snippets/main/src/Quest-Completer-ES.js")).text());
  ```

<details>
  <summary>How to use</summary>

  1. Accept a quest under the ``Quests`` tab
  2. Press ``Ctrl`` + ``Shift`` + ``I`` to open DevTools
  3. Go to the ``Console`` tab
  4. Paste the code above (the English or the Spanish version) and press ``Enter``
  5. Dependig on the type of the quest:
     - Play / Watch video: Just wait and do nothing
     - Stream: Join a VC with a friend/alt account and stream any window
  6. Wait a bit for it to complete the quest
  7. You can now claim the reward
</details>

\
**Posible issues**

<details>
  <summary>When I press Ctrl + Shift + I nothing happens</summary>

  1. Go to your Discord installation folder, usually in ``%appdata%\discord\``
  2. Open the ``settings.json`` file (if it doesn't exist, create it)
  3. Paste the code below:
     - If it's just copy and paste this: 
        ```json
        {
          "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true
        }
        ```
     - Otherwise, below the ``{`` add a line and copy and paste this:
        ```json
          "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true,
        ```
        It has to be like this:
        ```json
        {
          "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true,
          "other_option": value,
          "another_option": value
        }
  4. Save and close the file
  5. End the Discord task completely and open it again
</details>

<details>
  <summary>I can't paste the code in the Console</summary>

  1. Type ``allow pasting`` in the console
  2. Press ``Enter``
  3. Paste the code again
</details>

<details>
  <summary>It throws an error in the console</summary>

  If you are sure that you are doing everything right, wait until I fix it, I'll try to fix it as soon as possible. You always can check the [opened issues](https://github.com/HerraHabibi/discord-snippets/issues) and if it doesn't exist, create it.
</details>

<details>
  <summary>I have a doubt, error not mentioned above or suggestion</summary>

  Please check the [opened issues](https://github.com/HerraHabibi/discord-snippets/issues) and if it doesn't exist, create it. I will try to resolve it as soon as possible.
</details>

<hr>

### Style Snippets Installation Guide

<details>
  <summary>Vencord Guide</summary>
  
  1. Press the Discord settings button
  \
  ![Step 1](https://i.imgur.com/8p3KjVH.png)
  2. Scroll down to the "Vencord" section, click on the "Vencord" tab and press the "Edit QuickCSS" button
  \
  ![Step 2](https://i.imgur.com/p4iciK7.png)
  3. In this popup, you must copy the code to apply the custom snippets and then you can close it
  \
  ![Step 3](https://i.imgur.com/dsNWmd3.png)
</details>

### Style Snippets

#### Hide Non VC Content On Active Now

Shows only the people in VCs on the active now tab

```css
@import url('https://raw.githubusercontent.com/HerraHabibi/discord-snippets/refs/heads/main/src/Hide-Non-Vc-Content-On-Active-Now.css');
```

<details>
  <summary>Before/After</summary>

  ![Hide Non VC Content On Active Now](https://i.imgur.com/PgunQLm.png)
</details>

#### Hide Activity On Server Member List

Hides the activity on the server member list

```css
@import url('https://raw.githubusercontent.com/HerraHabibi/discord-snippets/refs/heads/main/src/Hide-Activity-On-Server-Member-List.css');
```

<details>
  <summary>Before/After</summary>

  ![Hide Activity On Server Member List](https://i.imgur.com/WjzpCQO.png)
</details>

#### Hide Your Activity On Panel

Hides your own activity on the panel section (bottom left)

```css
@import url('https://raw.githubusercontent.com/HerraHabibi/discord-snippets/refs/heads/main/src/Hide-Your-Activity-On-Panel.css');
```

<details>
  <summary>Before/After</summary>

  ![Hide Your Activity On Panel](https://i.imgur.com/pwksupH.png)
</details>

#### Fix Cam Inverted

Fixes the bug that makes your own camera look inverted, so you see it the way others see it

```css
@import url('https://raw.githubusercontent.com/HerraHabibi/discord-snippets/refs/heads/main/src/Fix-Cam-Inverted.css');
```

<details>
  <summary>Before/After</summary>

  ![Fix Cam Inverted](https://i.imgur.com/LKTx3qP.png)
</details>