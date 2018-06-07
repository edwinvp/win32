---
Description: By setting the Factoid property to None, the character recognizer recognizes handwriting on a character-by-character basis.
ms.assetid: 4dacceab-032e-4b9b-858f-67961fd587b5
title: Word vs. Character Recognition
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Word vs. Character Recognition

By setting the [Factoid](https://www.bing.com/search?q=Factoid) property to **None**, the character recognizer recognizes handwriting on a character-by-character basis.

The [RecoTimeout](https://www.bing.com/search?q=RecoTimeout) ([**RecoTimeout**](/windows/desktop/api/inked/nf-inked-iinkedit-get_recognitiontimeout) in Automation) property specifies the number of milliseconds of delay between the last [Stroke](https://www.bing.com/search?q=Stroke) and the end of handwriting input. You can increase this value to recognize text before entire words or sentences are written. You can also force the recognition of ink immediately by using the [Recognize](https://www.bing.com/search?q=Recognize) method.

 

 


