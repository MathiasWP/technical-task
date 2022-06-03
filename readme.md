# Kvist technical task

**Mission:** Create a currency converter application with Svelte and TypeScript based on the design provided (Look at `./Design.png`).


### User stories

- As a user i want to click the name of the currency to change it .
    - Clicking on the currency should open a native option-list with the following currencies: _NOK_ and _IRR_.
    <p align="center">
    <img width="323" alt="info-1" src="https://user-images.githubusercontent.com/48158184/171905931-89ad9ce4-7940-404c-b72e-43be5e6e56db.png">
<p>
    
- As a user i want to type in the amount i want to convert and automatically see the result.
    - The user should only use the top input
    - The convertion should happen automatically, no need for clicking any buttons.


### Extra user story
This user story is not required.
    
- As a user i want to click the button in the middle to change the direction of the convertion.
    - By default the top input is the only input, but adding this feature requires also the bottom to behave as an input.  
    - Clicking the button should make the arrow turn 180 deg to clearly indicate the direction

 
## Assets:
    
### Currency converting
You are free to choose how you want to convert the currency. There's a lot of API's which can be used, but they usually require an API key. I understand if you don't want to sign up to these services for a free API key, so it's okay to hardcode the exchange rate conversions.:
    
- 1 IRR = 0.00022 NOK
- 1 NOK = 4482 IRR

### Colors
- **Red color hex:** `#eb5f57`  
- **White color hex:** `#faf8f9`

### Icon
SVG code for arrow icon:
    
```
<svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" fill="currentColor" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M8 1a.5.5 0 0 1 .5.5v11.793l3.146-3.147a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 .708-.708L7.5 13.293V1.5A.5.5 0 0 1 8 1z"/>
</svg>
```

## Guidance on using Svelte

**Svelte website:** https://svelte.dev
    
**Svelte docs:** https://svelte.dev/docs

I highly recommend going through the Svelte tutorial: https://svelte.dev/tutorial/basics

This tutorial gives full insight to Svelte. It is not required to complete all the steps. You can easily navigate through the different chapters and skip to the topics that are relevant/interesting for completing the task. 
    
If you like watching YouTube tutorials as well then i strongly recommend this channel: https://www.youtube.com/c/lihautan

    
### How to create a svelte project
The easiest way to set up a Svelte SPA with TypeScript is with [Vite](https://vitejs.dev/):

Type the following into your terminal `npm create vite@latest` and select the `svelte-ts` template
