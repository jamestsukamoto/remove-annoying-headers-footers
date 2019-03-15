# Remove Annoying Headers & Footers 😡
Get rid of those pesky, screen-hogging banners/footers on Medium blogs. On my 13" MacBook Pro, these banners can take up over 40% of the screen real estate, leaving only a small amount of text to read at a time. 

## Usage:
1. Navigate to the blog post you'd like to read
2. Open up your browser's developer/debug console
    - Shortcuts:
      - Chrome: `⌘ + ⌥ + J`
      - Safari: `⌘ + ⌥ + I`
      - Mozilla: `⌘ + ⌥ + K`
3. Copy code from below for the cooresponding website
4. Paste code into the browser console
5. Run code 
6. Star/Bookmark this repo for quick access!

## freeCodeCamp
    const topBar = document.querySelector('div.metabar.u-clearfix.js-metabar.u-textColorTransparentWhiteDarker.u-tintBgColor.u-tintSpectrum.u-fixed.u-backgroundTransparentWhiteDarkest.u-xs-sizeFullViewportWidth');
    
    const updateBanner = document.querySelector(' div.u-fixed.u-bottom0.u-width100pct.u-backgroundWhite.u-boxShadowTop.u-borderBox.u-paddingTop10.u-paddingBottom10.u-zIndexMetabar.u-xs-paddingLeft10.u-xs-paddingRight10.js-stickyFooter');
   
    topBar.remove();
    
    updateBanner.remove();

## Hackernoon

    const topBar = document.querySelector('div.metabar.u-clearfix.js-metabar.u-boxShadow4px12pxBlackLightest.u-textColorDarker.u-fixed.u-backgroundTransparentWhiteDarkest.u-xs-sizeFullViewportWidth');
    
    const updateBanner = document.querySelector('div.u-fixed.u-bottom0.u-width100pct.u-backgroundWhite.u-boxShadowTop.u-borderBox.u-paddingTop10.u-paddingBottom10.u-zIndexMetabar.u-xs-paddingLeft10.u-xs-paddingRight10.js-stickyFooter');
   
    topBar.remove();
    
    updateBanner.remove();
