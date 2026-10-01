# JSON to eLRC or TTML, Base 64 to JSON

These apps are simple, there is no fancy or complex UI, as well as there are no settings. They only have one function: convert.  
**1. Choose the file (or paste the Base64 text format).  
2. Press the button.  
3. Receive your converted file.**  

But it doesn't matter how simple they are, I'm here to show them and prove they work.

*Song chosen: "Ain't in LA" by ADÉLA, the track number 11 from her first studio album 'PRIMA', released on the 4th of September, 2026.*

## Base 64 to JSON (Gunzip)

Imagine you have entered the cache of one of your chrome extensions because the lyrics are there (a.k.a. Better Lyrics for YT Music (that's why the text has to be a compressed file with ``gzip``)) and you see this:

```json
{
"expiry": "1790871826455",
"type": "transient",
"value": "__COMPRESSED__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"
} 
```

Well, you only need the ``value`` part, so copy all that bunch of letter and numbers (with the ``__COMPRESSED__`` part included) and open the ``Base64.to.JSON.exe``.

<img width="366" height="170" alt="image" src="https://github.com/user-attachments/assets/06f4165c-295c-4ffa-b402-44e477782500" />

Paste the value, with the ``__COMPRESSED__`` part included.

<img width="333" height="147" alt="image" src="https://github.com/user-attachments/assets/4f9601a9-4d37-449a-a898-e3c7044a7f42" />

And press "ok".  
It will generate the ``.json`` file and ask you to put the name and select the path.

Just save it and you're good to go (I know the app it's in Spanish, but that's why I'm doing this, so everybody understands).

If everything went good, this message appears:

<img width="407" height="190" alt="image" src="https://github.com/user-attachments/assets/1356a307-608c-453f-b9a6-010b148bfc73" />

Just click ``Aceptar`` (ok) and that's it.

## JSON to eLRC

Once you have the ``-json`` file, you can either keep it, or convert it. In case you wanna convert it, you've got two ways, the first one is eLRC (Enhanced LRC), supporting:

- Multi-Singers.
- Background Vocals.
- Correct implementation of the ``<...>`` tags at the end of a line, so every player can render and read it properly.

So, we've got our JSON from the ``Base64.to.JSON.exe`` app that looks like this (I'm putting two singers + BGV for the example, and it's only the first chorus and the first verse):

```json
{
  "version": "2.1.0",
  "cacheAllowed": true,
  "language": "en",
  "lyrics": [
    {
      "startTimeMs": 0,
      "durationMs": 2725,
      "words": "",
      "parts": [],
      "isInstrumental": true
    },
    {
      "agent": "v2",
      "durationMs": 3595,
      "parts": [
        {
          "startTimeMs": 16678,
          "durationMs": 200,
          "isBackground": false,
          "words": "Back",
          "explicit": false
        },
        {
          "startTimeMs": 16878,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 16878,
          "durationMs": 198,
          "isBackground": false,
          "words": "it",
          "explicit": false
        },
        {
          "startTimeMs": 17076,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 17076,
          "durationMs": 401,
          "isBackground": false,
          "words": "up,",
          "explicit": false
        },
        {
          "startTimeMs": 17477,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 17477,
          "durationMs": 796,
          "isBackground": false,
          "words": "subwoofers",
          "explicit": false
        },
        {
          "startTimeMs": 18273,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 18273,
          "durationMs": 199,
          "isBackground": false,
          "words": "in",
          "explicit": false
        },
        {
          "startTimeMs": 18472,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 18472,
          "durationMs": 398,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 18870,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 18870,
          "durationMs": 398,
          "isBackground": false,
          "words": "trunk,",
          "explicit": false
        },
        {
          "startTimeMs": 19268,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 19268,
          "durationMs": 200,
          "isBackground": false,
          "words": "and",
          "explicit": false
        },
        {
          "startTimeMs": 19468,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 19468,
          "durationMs": 597,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 16325,
          "durationMs": 4936,
          "isBackground": true,
          "words": "(Aah-aah-aah)",
          "explicit": false
        }
      ],
      "startTimeMs": 16325,
      "words": "Back it up, subwoofers in the trunk, and the",
      "key": "L5"
    },
    {
      "agent": "v2",
      "durationMs": 7770,
      "parts": [
        {
          "startTimeMs": 20065,
          "durationMs": 999,
          "isBackground": false,
          "words": "Gemstones",
          "explicit": false
        },
        {
          "startTimeMs": 21064,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 21064,
          "durationMs": 197,
          "isBackground": false,
          "words": "in",
          "explicit": false
        },
        {
          "startTimeMs": 21261,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 21261,
          "durationMs": 398,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 21659,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 21659,
          "durationMs": 199,
          "isBackground": false,
          "words": "teeth",
          "explicit": false
        },
        {
          "startTimeMs": 21858,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 21858,
          "durationMs": 406,
          "isBackground": false,
          "words": "go",
          "explicit": false
        },
        {
          "startTimeMs": 22264,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 22264,
          "durationMs": 383,
          "isBackground": false,
          "words": "dumb,",
          "explicit": false
        },
        {
          "startTimeMs": 22647,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 22647,
          "durationMs": 206,
          "isBackground": false,
          "words": "and",
          "explicit": false
        },
        {
          "startTimeMs": 22853,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 22853,
          "durationMs": 599,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 22452,
          "durationMs": 5383,
          "isBackground": true,
          "words": "(Aah-aah-aah)",
          "explicit": false
        }
      ],
      "startTimeMs": 20065,
      "words": "Gemstones in the teeth go dumb, and the",
      "key": "L6"
    },
    {
      "agent": "v2",
      "durationMs": 3586,
      "parts": [
        {
          "startTimeMs": 23452,
          "durationMs": 198,
          "isBackground": false,
          "words": "Light",
          "explicit": false
        },
        {
          "startTimeMs": 23650,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 23650,
          "durationMs": 399,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 24049,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 24049,
          "durationMs": 798,
          "isBackground": false,
          "words": "cigarette",
          "explicit": false
        },
        {
          "startTimeMs": 24847,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 24847,
          "durationMs": 192,
          "isBackground": false,
          "words": "with",
          "explicit": false
        },
        {
          "startTimeMs": 25039,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 25039,
          "durationMs": 206,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 25245,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 25245,
          "durationMs": 1793,
          "isBackground": false,
          "words": "propane",
          "explicit": false
        }
      ],
      "startTimeMs": 23452,
      "words": "Light the cigarette with the propane",
      "key": "L7"
    },
    {
      "agent": "v2",
      "durationMs": 2987,
      "parts": [
        {
          "startTimeMs": 27038,
          "durationMs": 398,
          "isBackground": false,
          "words": "Honda",
          "explicit": false
        },
        {
          "startTimeMs": 27436,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 27436,
          "durationMs": 399,
          "isBackground": false,
          "words": "Civic",
          "explicit": false
        },
        {
          "startTimeMs": 27835,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 27835,
          "durationMs": 199,
          "isBackground": false,
          "words": "doing",
          "explicit": false
        },
        {
          "startTimeMs": 28034,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 28034,
          "durationMs": 199,
          "isBackground": false,
          "words": "donuts",
          "explicit": false
        },
        {
          "startTimeMs": 28233,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 28233,
          "durationMs": 598,
          "isBackground": false,
          "words": "in",
          "explicit": false
        },
        {
          "startTimeMs": 28831,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 28831,
          "durationMs": 192,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 29023,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 29023,
          "durationMs": 1002,
          "isBackground": false,
          "words": "rain",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 29255,
          "durationMs": 770,
          "isBackground": true,
          "words": "(Ah)",
          "explicit": false
        }
      ],
      "startTimeMs": 27038,
      "words": "Honda Civic doing donuts in the rain",
      "key": "L8"
    },
    {
      "agent": "v1",
      "durationMs": 3388,
      "parts": [
        {
          "startTimeMs": 30025,
          "durationMs": 400,
          "isBackground": false,
          "words": "She",
          "explicit": false
        },
        {
          "startTimeMs": 30425,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 30425,
          "durationMs": 200,
          "isBackground": false,
          "words": "shares",
          "explicit": false
        },
        {
          "startTimeMs": 30625,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 30625,
          "durationMs": 209,
          "isBackground": false,
          "words": "a",
          "explicit": false
        },
        {
          "startTimeMs": 30834,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 30834,
          "durationMs": 579,
          "isBackground": false,
          "words": "room",
          "explicit": false
        },
        {
          "startTimeMs": 31413,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 31413,
          "durationMs": 206,
          "isBackground": false,
          "words": "with",
          "explicit": false
        },
        {
          "startTimeMs": 31619,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 31619,
          "durationMs": 200,
          "isBackground": false,
          "words": "her",
          "explicit": false
        },
        {
          "startTimeMs": 31819,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 31819,
          "durationMs": 789,
          "isBackground": false,
          "words": "younger",
          "explicit": false
        },
        {
          "startTimeMs": 32608,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 32608,
          "durationMs": 805,
          "isBackground": false,
          "words": "brother",
          "explicit": false
        }
      ],
      "startTimeMs": 30025,
      "words": "She shares a room with her younger brother",
      "key": "L9"
    },
    {
      "agent": "v1",
      "durationMs": 3586,
      "parts": [
        {
          "startTimeMs": 33413,
          "durationMs": 597,
          "isBackground": false,
          "words": "Clothes",
          "explicit": false
        },
        {
          "startTimeMs": 34010,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 34010,
          "durationMs": 797,
          "isBackground": false,
          "words": "secondhand",
          "explicit": false
        },
        {
          "startTimeMs": 34807,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 34807,
          "durationMs": 192,
          "isBackground": false,
          "words": "from",
          "explicit": false
        },
        {
          "startTimeMs": 34999,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 34999,
          "durationMs": 206,
          "isBackground": false,
          "words": "her",
          "explicit": false
        },
        {
          "startTimeMs": 35205,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 35205,
          "durationMs": 394,
          "isBackground": false,
          "words": "best",
          "explicit": false
        },
        {
          "startTimeMs": 35599,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 35599,
          "durationMs": 404,
          "isBackground": false,
          "words": "friend's",
          "explicit": false
        },
        {
          "startTimeMs": 36003,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 36003,
          "durationMs": 996,
          "isBackground": false,
          "words": "mother",
          "explicit": false
        }
      ],
      "startTimeMs": 33413,
      "words": "Clothes secondhand from her best friend's mother",
      "key": "L10"
    },
    {
      "agent": "v1",
      "durationMs": 3314,
      "parts": [
        {
          "startTimeMs": 36999,
          "durationMs": 202,
          "isBackground": false,
          "words": "Cut",
          "explicit": false
        },
        {
          "startTimeMs": 37201,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 37201,
          "durationMs": 196,
          "isBackground": false,
          "words": "'em",
          "explicit": false
        },
        {
          "startTimeMs": 37397,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 37397,
          "durationMs": 399,
          "isBackground": false,
          "words": "all",
          "explicit": false
        },
        {
          "startTimeMs": 37796,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 37796,
          "durationMs": 398,
          "isBackground": false,
          "words": "up,",
          "explicit": false
        },
        {
          "startTimeMs": 38194,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 38194,
          "durationMs": 398,
          "isBackground": false,
          "words": "yeah,",
          "explicit": false
        },
        {
          "startTimeMs": 38592,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 38592,
          "durationMs": 200,
          "isBackground": false,
          "words": "she",
          "explicit": false
        },
        {
          "startTimeMs": 38792,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 38792,
          "durationMs": 191,
          "isBackground": false,
          "words": "got",
          "explicit": false
        },
        {
          "startTimeMs": 38983,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 38983,
          "durationMs": 207,
          "isBackground": false,
          "words": "her",
          "explicit": false
        },
        {
          "startTimeMs": 39190,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 39190,
          "durationMs": 199,
          "isBackground": false,
          "words": "own",
          "explicit": false
        },
        {
          "startTimeMs": 39389,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 39389,
          "durationMs": 924,
          "isBackground": false,
          "words": "style",
          "explicit": false
        }
      ],
      "startTimeMs": 36999,
      "words": "Cut 'em all up, yeah, she got her own style",
      "key": "L11"
    },
    {
      "agent": "v1",
      "durationMs": 3857,
      "parts": [
        {
          "startTimeMs": 40313,
          "durationMs": 527,
          "isBackground": false,
          "words": "Madonna",
          "explicit": false
        },
        {
          "startTimeMs": 40840,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 40840,
          "durationMs": 153,
          "isBackground": false,
          "words": "on",
          "explicit": false
        },
        {
          "startTimeMs": 40993,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 40993,
          "durationMs": 207,
          "isBackground": false,
          "words": "the",
          "explicit": false
        },
        {
          "startTimeMs": 41200,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 41200,
          "durationMs": 380,
          "isBackground": false,
          "words": "wall",
          "explicit": false
        },
        {
          "startTimeMs": 41580,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 41580,
          "durationMs": 200,
          "isBackground": false,
          "words": "next",
          "explicit": false
        },
        {
          "startTimeMs": 41780,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 41780,
          "durationMs": 398,
          "isBackground": false,
          "words": "to",
          "explicit": false
        },
        {
          "startTimeMs": 42178,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 42178,
          "durationMs": 599,
          "isBackground": false,
          "words": "Destiny's",
          "explicit": false
        },
        {
          "startTimeMs": 42777,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 42777,
          "durationMs": 1393,
          "isBackground": false,
          "words": "Child",
          "explicit": false
        }
      ],
      "startTimeMs": 40313,
      "words": "Madonna on the wall next to Destiny's Child",
      "key": "L12"
    },
    {
      "agent": "v1",
      "durationMs": 3029,
      "parts": [
        {
          "startTimeMs": 44170,
          "durationMs": 192,
          "isBackground": false,
          "words": "And",
          "explicit": false
        },
        {
          "startTimeMs": 44362,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 44362,
          "durationMs": 208,
          "isBackground": false,
          "words": "she's",
          "explicit": false
        },
        {
          "startTimeMs": 44570,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 44570,
          "durationMs": 596,
          "isBackground": false,
          "words": "all",
          "explicit": false
        },
        {
          "startTimeMs": 45166,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 45166,
          "durationMs": 1397,
          "isBackground": false,
          "words": "that",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 45933,
          "durationMs": 1266,
          "isBackground": true,
          "words": "(Eh-eh-eh-eh)",
          "explicit": false
        }
      ],
      "startTimeMs": 44170,
      "words": "And she's all that",
      "key": "L13"
    },
    {
      "agent": "v1",
      "durationMs": 4381,
      "parts": [
        {
          "startTimeMs": 46563,
          "durationMs": 396,
          "isBackground": false,
          "words": "'Cause",
          "explicit": false
        },
        {
          "startTimeMs": 46959,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 46959,
          "durationMs": 200,
          "isBackground": false,
          "words": "she",
          "explicit": false
        },
        {
          "startTimeMs": 47159,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 47159,
          "durationMs": 398,
          "isBackground": false,
          "words": "knows",
          "explicit": false
        },
        {
          "startTimeMs": 47557,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 47557,
          "durationMs": 300,
          "isBackground": false,
          "words": "she's",
          "explicit": false
        },
        {
          "startTimeMs": 47857,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 47956,
          "durationMs": 397,
          "isBackground": false,
          "words": "beau",
          "explicit": false
        },
        {
          "startTimeMs": 48353,
          "durationMs": 284,
          "isBackground": false,
          "words": "ti",
          "explicit": false
        },
        {
          "startTimeMs": 48637,
          "durationMs": 865,
          "isBackground": false,
          "words": "ful",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 49975,
          "durationMs": 969,
          "isBackground": true,
          "words": "(Ah-ah)",
          "explicit": false
        }
      ],
      "startTimeMs": 46563,
      "words": "'Cause she knows she's beautiful",
      "key": "L14"
    },
    {
      "agent": "v1",
      "durationMs": 3107,
      "parts": [
        {
          "startTimeMs": 50944,
          "durationMs": 205,
          "isBackground": false,
          "words": "And",
          "explicit": false
        },
        {
          "startTimeMs": 51149,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 51149,
          "durationMs": 186,
          "isBackground": false,
          "words": "she's",
          "explicit": false
        },
        {
          "startTimeMs": 51335,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 51335,
          "durationMs": 598,
          "isBackground": false,
          "words": "taught",
          "explicit": false
        },
        {
          "startTimeMs": 51933,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 51933,
          "durationMs": 1601,
          "isBackground": false,
          "words": "that",
          "explicit": false
        },
        {
          "startTimeMs": 0,
          "durationMs": 0,
          "isBackground": true,
          "words": "",
          "explicit": false
        },
        {
          "startTimeMs": 52785,
          "durationMs": 1266,
          "isBackground": true,
          "words": "(Eh-eh-eh-eh)",
          "explicit": false
        }
      ],
      "startTimeMs": 50944,
      "words": "And she's taught that",
      "key": "L15"
    },
    {
      "agent": "v1",
      "durationMs": 2791,
      "parts": [
        {
          "startTimeMs": 53534,
          "durationMs": 192,
          "isBackground": false,
          "words": "Her",
          "explicit": false
        },
        {
          "startTimeMs": 53726,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 53726,
          "durationMs": 803,
          "isBackground": false,
          "words": "dreams",
          "explicit": false
        },
        {
          "startTimeMs": 54529,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 54529,
          "durationMs": 200,
          "isBackground": false,
          "words": "don't",
          "explicit": false
        },
        {
          "startTimeMs": 54729,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 54729,
          "durationMs": 192,
          "isBackground": false,
          "words": "live",
          "explicit": false
        },
        {
          "startTimeMs": 54921,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 54921,
          "durationMs": 300,
          "isBackground": false,
          "words": "at",
          "explicit": false
        },
        {
          "startTimeMs": 55221,
          "durationMs": 0,
          "isBackground": false,
          "words": " "
        },
        {
          "startTimeMs": 55326,
          "durationMs": 999,
          "isBackground": false,
          "words": "home",
          "explicit": false
        }
      ],
      "startTimeMs": 53534,
      "words": "Her dreams don't live at home",
      "key": "L16"
    }
  ],
  "musicVideoSynced": false,
  "source": "betterlyrics.org",
  "sourceHref": "https://betterlyrics.org"
}
```

Now, we open up the app ``JSON.to.eLRC.exe``

<img width="566" height="326" alt="image" src="https://github.com/user-attachments/assets/4ccb88f2-7170-4486-bfb9-727cd8e1314d" />

Click on the green button and choose the ``.json`` file you've just created.

<img width="937" height="592" alt="image" src="https://github.com/user-attachments/assets/f8818e2f-dfd4-40ca-833f-5644a77f9459" />

Open it and let the app do the magic.  
It will save the file with the same name the ``.json`` file had and **in the same path**. The extension now is ``.elrc``, open it with **the Notepad app**.
This message will appear.

<img width="382" height="190" alt="image" src="https://github.com/user-attachments/assets/3a2f9b07-fecd-4739-b256-7b6fcea5f800" />

Now, we have the eLRC (this is the FULL eLRC):

```elrc
[ti: JSON_Example]
[by: Enhanced LRC Converter]

[00:02.73] v2: <00:02.73>Back <00:02.93>it <00:03.13>up, <00:03.73>subwoofers <00:04.52>in <00:04.73>the <00:04.92>trunk, <00:05.32>and <00:05.52>the<00:06.32>
[00:06.32] v2: <00:06.32>Gemstones <00:07.32>in <00:07.46>the <00:07.71>teeth <00:07.92>go <00:08.31>dumb, <00:08.91>and <00:09.10>the<00:09.70>
[00:09.70] v2: <00:09.70>Light <00:09.90>the <00:10.30>cigarette <00:11.10>with <00:11.30>the <00:11.49>propane<00:13.09>
[00:13.09] v2: <00:13.09>Honda <00:13.49>Civic <00:13.88>doing <00:14.29>donuts <00:14.88>in <00:15.08>the <00:15.28>rain<00:16.68>
[00:16.68] v2: <00:16.68>Back <00:16.88>it <00:17.08>up, <00:17.48>subwoofers <00:18.27>in <00:18.47>the <00:18.87>trunk, <00:19.27>and <00:19.47>the<00:20.07>
[bg: <00:16.32><00:16.32>(Aah-aah-aah)<00:21.26>]
[00:20.07] v2: <00:20.07>Gemstones <00:21.06>in <00:21.26>the <00:21.66>teeth <00:21.86>go <00:22.26>dumb, <00:22.65>and <00:22.85>the<00:23.45>
[bg: <00:22.45><00:22.45>(Aah-aah-aah)<00:27.84>]
[00:23.45] v2: <00:23.45>Light <00:23.65>the <00:24.05>cigarette <00:24.85>with <00:25.04>the <00:25.25>propane<00:27.04>
[00:27.04] v2: <00:27.04>Honda <00:27.44>Civic <00:27.84>doing <00:28.03>donuts <00:28.23>in <00:28.83>the <00:29.02>rain<00:30.02>
[bg: <00:29.25><00:29.25>(Ah)<00:30.02>]
[00:30.02] v1: <00:30.02>She <00:30.43>shares <00:30.62>a <00:30.83>room <00:31.41>with <00:31.62>her <00:31.82>younger <00:32.61>brother<00:33.41>
[00:33.41] v1: <00:33.41>Clothes <00:34.01>secondhand <00:34.81>from <00:35.00>her <00:35.20>best <00:35.60>friend's <00:36.00>mother<00:37.00>
[00:37.00] v1: <00:37.00>Cut <00:37.20>'em <00:37.40>all <00:37.80>up, <00:38.19>yeah, <00:38.59>she <00:38.79>got <00:38.98>her <00:39.19>own <00:39.39>style<00:40.31>
[00:40.31] v1: <00:40.31>Madonna <00:40.84>on <00:40.99>the <00:41.20>wall <00:41.58>next <00:41.78>to <00:42.18>Destiny's <00:42.78>Child<00:44.17>
[00:44.17] v1: <00:44.17>And <00:44.36>she's <00:44.57>all <00:45.17>that<00:46.56>
[bg: <00:45.93><00:45.93>(Eh-eh-eh-eh)<00:47.20>]
[00:46.56] v1: <00:46.56>'Cause <00:46.96>she <00:47.16>knows <00:47.56>she's <00:47.96>beau<00:48.35>ti<00:48.64>ful<00:49.50>
[bg: <00:49.98><00:49.98>(Ah-ah)<00:50.94>]
[00:50.94] v1: <00:50.94>And <00:51.15>she's <00:51.34>taught <00:51.93>that<00:53.53>
[bg: <00:52.78><00:52.78>(Eh-eh-eh-eh)<00:54.05>]
[00:53.53] v1: <00:53.53>Her <00:53.73>dreams <00:54.53>don't <00:54.73>live <00:54.92>at <00:55.33>home<00:56.33>
[00:56.33] v1: <00:56.33>May<00:56.92>be <00:57.32>to<00:57.64>night<00:59.31>
[00:59.31] v1: <00:59.31>We <00:59.71>don't <00:59.91>gotta <01:00.10>run <01:00.76>a<01:00.94>way<01:03.09>
[01:03.09] v1: <01:03.09>It's <01:03.49>all <01:04.09>a <01:04.46>lie<01:06.08>
[01:06.08] v1: <01:06.08>The <01:06.48>baddest <01:06.81>bitches <01:07.08>ain't <01:07.28>in <01:07.48>L.<01:07.89>A.<01:10.06>
[01:10.06] v1: <01:10.06>En<01:10.65>joy <01:11.07>the <01:11.38>ride<01:13.05>
[01:13.05] v1: <01:13.05>I <01:13.26>know <01:13.45>that <01:13.65>you <01:13.86>might <01:14.13>wanna <01:14.45>es<01:14.63>cape<01:17.04>
[01:17.04] v1: <01:17.04>It's <01:17.44>all <01:17.84>a <01:18.22>lie<01:20.02>
[01:20.02] v1: <01:20.02>The <01:20.23>baddest <01:20.62>bitches <01:20.98>ain't <01:21.23>in <01:21.42>L.<01:21.62>A.<01:25.20>
[bg: <01:25.25><01:25.25>(Ah-ah)<01:29.94>]
[01:25.61] v2: <01:25.61>Back <01:25.81>it <01:26.00>up, <01:26.60>subwoofers <01:27.40>in <01:27.60>the <01:27.80>trunk, <01:28.40>and <01:28.60>the<01:29.19>
[01:29.19] v2: <01:29.19>Gemstones <01:29.98>in <01:30.19>the <01:30.58>teeth <01:30.99>go <01:31.19>dumb, <01:31.78>and <01:31.98>the<01:32.58>
[bg: <01:31.89><01:31.89>(Ah-ah-ah)<01:36.18>]
[01:32.58] v2: <01:32.58>Light <01:32.97>the <01:33.18>cigarette <01:33.78>with <01:33.97>the <01:34.39>propane<01:36.18>
[01:36.18] v2: <01:36.18>Honda <01:36.38>Civic <01:36.97>doing <01:37.37>donuts <01:37.57>in <01:37.77>the <01:37.98>rain<01:38.96>
[bg: <01:38.39><01:38.39>(Ah)<01:39.56>]
[01:38.96] v1: <01:38.96>All <01:39.56>of <01:39.77>the <01:39.96>girls <01:40.36>in <01:40.57>them <01:40.96>unknown <01:41.61>cities<01:42.55>
[01:42.55] v1: <01:42.55>You're <01:42.95>so <01:43.15>unique <01:43.75>and <01:43.95>your <01:44.35>face <01:44.74>so <01:45.14>pretty<01:46.34>
[01:46.34] v1: <01:46.34>Don't <01:46.53>look <01:46.74>like <01:46.94>anyone<01:47.93>
[01:47.93] v1: <01:47.93>You're <01:48.13>not <01:48.33>just <01:48.73>anyone<01:49.33>
[01:49.33] v1: <01:49.33>I'd <01:49.52>rather <01:49.72>be <01:49.92>a <01:50.32>nobody <01:51.12>than <01:51.32>to <01:51.52>be <01:51.72>like <01:52.01>everyone<01:53.11>
[01:53.11] v1: <01:53.11>And <01:53.31>you're <01:53.52>all <01:54.12>that<01:55.09>
[bg: <01:54.93><01:54.93>(Eh-eh-eh-eh)<01:56.20>]
[01:55.49] v1: <01:55.49>'Cause <01:56.09>you <01:56.38>know <01:56.87>you're <01:57.28>beautiful<01:58.23>
[bg: <01:58.97><01:58.97>(Ah-ah)<01:59.79>]
[01:59.94] v1: <01:59.94>And <02:00.41>you're <02:00.73>taught <02:01.12>that<02:02.82>
[bg: <02:01.78><02:01.78>(Eh-eh-eh-eh)<02:03.05>]
[02:02.82] v1: <02:02.82>Your <02:03.18>dreams <02:03.68>don't <02:04.11>live <02:04.34>at <02:04.52>home<02:04.98>
[02:05.29] v1: <02:05.29>May<02:05.89>be <02:06.28>to<02:06.60>night<02:08.28>
[02:08.28] v1: <02:08.28>We <02:08.67>don't <02:08.87>gotta <02:09.06>run <02:09.72>a<02:09.90>way<02:12.05>
[02:12.05] v1: <02:12.05>It's <02:12.46>all <02:13.06>a <02:13.42>lie<02:15.04>
[02:15.04] v1: <02:15.04>The <02:15.45>baddest <02:15.78>bitches <02:16.05>ain't <02:16.25>in <02:16.44>L.<02:16.86>A.<02:19.03>
[02:19.03] v1: <02:19.03>En<02:19.61>joy <02:20.03>the <02:20.34>ride<02:22.01>
[02:22.01] v1: <02:22.01>I <02:22.22>know <02:22.42>that <02:22.61>you <02:22.83>might <02:23.10>wanna <02:23.42>es<02:23.60>cape<02:26.01>
[02:26.01] v1: <02:26.01>It's <02:26.41>all <02:26.80>a <02:27.18>lie<02:28.99>
[02:28.99] v1: <02:28.99>The <02:29.19>baddest <02:29.59>bitches <02:29.93>ain't <02:30.19>in <02:30.39>L.<02:30.58>A.<02:34.17>
[bg: <02:34.21><02:34.21>(Ah-ah)<02:38.90>]
[02:34.57] v2: <02:34.57>Back <02:34.77>it <02:34.96>up, <02:35.56>subwoofers <02:36.36>in <02:36.56>the <02:36.76>trunk, <02:37.36>and <02:37.56>the<02:38.15>
[02:38.15] v2: <02:38.15>Gemstones <02:38.94>in <02:39.15>the <02:39.54>teeth <02:39.94>go <02:40.15>dumb, <02:40.74>and <02:40.94>the<02:41.54>
[bg: <02:40.85><02:40.85>(Ah-ah-ah)<02:45.14>]
[02:41.54] v2: <02:41.54>Light <02:41.93>the <02:42.14>cigarette <02:42.73>with <02:42.93>the <02:43.34>propane<02:45.14>
[bg: <02:41.93><02:41.93>(Yeah, <02:42.55>yeah, <02:43.56>oh-<02:44.02>oh)<02:45.14>]
[02:45.14] v2: <02:45.14>Honda <02:45.34>Civic <02:45.93>doing <02:46.33>donuts <02:46.53>in <02:46.72>the <02:46.93>rain<02:47.92>
[02:46.68] v2000: <02:46.68>May<02:47.28>be <02:47.68>to<02:48.00>night<02:49.67>
[bg: <02:49.00><02:49.00>(Ah-ah-ah)<02:53.28>]
[02:49.67] v2000: <02:49.67>We <02:50.07>don't <02:50.27>gotta <02:50.46>run <02:51.12>a<02:51.29>way<02:53.45>
[bg: <02:51.98><02:51.98>(No)<02:55.63>]
[02:53.45] v2000: <02:53.45>It's <02:53.85>all <02:54.45>a <02:54.82>lie<02:56.44>
[bg: <02:55.95><02:55.95>(Oh)<02:56.46>]
[02:56.44] v2000: <02:56.44>The <02:56.84>baddest <02:57.17>bitches <02:57.52>ain't <02:57.72>in <02:57.99>L.<02:58.25>A.<03:01.97>
```
The double ``<...>`` (time tag) at the begging of the ``[bg:...]`` part is because one represents the start of the whole background vocals part and the other the start of the fist background vocal word.  
They don't cause any trouble, so don't worry. :D

But you've got what I said:

- Multi-Singer support with those ``v1:``, ``v2:`` and ``v2000:`` tags.
- The background vocals with the ``[bg: <...>(...) <...>]`` part.
- The end tags at the end of the last word in the line, so players can read the eLRC perfectly.

#### ***You've made it, you created your own eLRC!***

## JSON to TTML

The steps are the same.

Open the app.

<img width="626" height="413" alt="image" src="https://github.com/user-attachments/assets/3effa20b-c499-432e-8338-c2cd72f7120c" />

Click ``Importar JSON`` (import JSON).  
Select your ``.json`` file and open it.  
The ``.ttml`` file will be generated and it will ask you to select the path where you want to save it.  
The name is the same as the original ``.json`` file.

If everything went good, you'll receive this pop-up:

<img width="330" height="200" alt="image" src="https://github.com/user-attachments/assets/8a45456d-e3c0-476b-9b71-b49d5a6693c9" />

Saying that the ``.ttml`` file has been created correctly.

And here we have it (first full chorus and first verse):

```xml
<?xml version="1.0" encoding="UTF-8"?>
<tt xmlns="http://w3.org" xmlns:ttm="http://w3.org#metadata">
  <body>
    <div>
      <p begin="00:00:02.72" end="00:00:06.32" ttm:agent="v2">
        <span begin="00:00:02.72" end="00:00:02.93">Back </span>
        <span begin="00:00:02.93" end="00:00:03.13">it </span>
        <span begin="00:00:03.13" end="00:00:03.73">up, </span>
        <span begin="00:00:03.73" end="00:00:04.52">subwoofers </span>
        <span begin="00:00:04.52" end="00:00:04.73">in </span>
        <span begin="00:00:04.73" end="00:00:04.92">the </span>
        <span begin="00:00:04.92" end="00:00:05.32">trunk, </span>
        <span begin="00:00:05.32" end="00:00:05.52">and </span>
        <span begin="00:00:05.52" end="00:00:06.32">the</span>
      </p>
      <p begin="00:00:06.32" end="00:00:09.70" ttm:agent="v2">
        <span begin="00:00:06.32" end="00:00:07.32">Gemstones </span>
        <span begin="00:00:07.32" end="00:00:07.46">in </span>
        <span begin="00:00:07.46" end="00:00:07.71">the </span>
        <span begin="00:00:07.71" end="00:00:07.92">teeth </span>
        <span begin="00:00:07.92" end="00:00:08.31">go </span>
        <span begin="00:00:08.31" end="00:00:08.91">dumb, </span>
        <span begin="00:00:08.91" end="00:00:09.10">and </span>
        <span begin="00:00:09.10" end="00:00:09.70">the</span>
      </p>
      <p begin="00:00:09.70" end="00:00:13.09" ttm:agent="v2">
        <span begin="00:00:09.70" end="00:00:09.90">Light </span>
        <span begin="00:00:09.90" end="00:00:10.30">the </span>
        <span begin="00:00:10.30" end="00:00:11.10">cigarette </span>
        <span begin="00:00:11.10" end="00:00:11.30">with </span>
        <span begin="00:00:11.30" end="00:00:11.49">the </span>
        <span begin="00:00:11.49" end="00:00:13.09">propane</span>
      </p>
      <p begin="00:00:13.09" end="00:00:16.68" ttm:agent="v2">
        <span begin="00:00:13.09" end="00:00:13.49">Honda </span>
        <span begin="00:00:13.49" end="00:00:13.88">Civic </span>
        <span begin="00:00:13.88" end="00:00:14.29">doing </span>
        <span begin="00:00:14.29" end="00:00:14.88">donuts </span>
        <span begin="00:00:14.88" end="00:00:15.08">in </span>
        <span begin="00:00:15.08" end="00:00:15.28">the </span>
        <span begin="00:00:15.28" end="00:00:16.68">rain</span>
      </p>
      <p begin="00:00:16.32" end="00:00:20.06" ttm:agent="v2">
        <span begin="00:00:16.68" end="00:00:16.88">Back </span>
        <span begin="00:00:16.88" end="00:00:17.08">it </span>
        <span begin="00:00:17.08" end="00:00:17.48">up, </span>
        <span begin="00:00:17.48" end="00:00:18.27">subwoofers </span>
        <span begin="00:00:18.27" end="00:00:18.47">in </span>
        <span begin="00:00:18.47" end="00:00:18.87">the </span>
        <span begin="00:00:18.87" end="00:00:19.27">trunk, </span>
        <span begin="00:00:19.27" end="00:00:19.47">and </span>
        <span begin="00:00:19.47" end="00:00:20.06">the</span>
        <span ttm:role="x-bg">
            <span begin="00:00:16.32" end="00:00:21.26">(Aah-aah-aah)</span>
        </span>
      </p>
      <p begin="00:00:20.06" end="00:00:23.45" ttm:agent="v2">
        <span begin="00:00:20.06" end="00:00:21.06">Gemstones </span>
        <span begin="00:00:21.06" end="00:00:21.26">in </span>
        <span begin="00:00:21.26" end="00:00:21.66">the </span>
        <span begin="00:00:21.66" end="00:00:21.86">teeth </span>
        <span begin="00:00:21.86" end="00:00:22.26">go </span>
        <span begin="00:00:22.26" end="00:00:22.65">dumb, </span>
        <span begin="00:00:22.65" end="00:00:22.85">and </span>
        <span begin="00:00:22.85" end="00:00:23.45">the</span>
        <span ttm:role="x-bg">
            <span begin="00:00:22.45" end="00:00:27.84">(Aah-aah-aah)</span>
        </span>
      </p>
      <p begin="00:00:23.45" end="00:00:27.04" ttm:agent="v2">
        <span begin="00:00:23.45" end="00:00:23.65">Light </span>
        <span begin="00:00:23.65" end="00:00:24.05">the </span>
        <span begin="00:00:24.05" end="00:00:24.85">cigarette </span>
        <span begin="00:00:24.85" end="00:00:25.04">with </span>
        <span begin="00:00:25.04" end="00:00:25.24">the </span>
        <span begin="00:00:25.24" end="00:00:27.04">propane</span>
      </p>
      <p begin="00:00:27.04" end="00:00:30.02" ttm:agent="v2">
        <span begin="00:00:27.04" end="00:00:27.44">Honda </span>
        <span begin="00:00:27.44" end="00:00:27.84">Civic </span>
        <span begin="00:00:27.84" end="00:00:28.03">doing </span>
        <span begin="00:00:28.03" end="00:00:28.23">donuts </span>
        <span begin="00:00:28.23" end="00:00:28.83">in </span>
        <span begin="00:00:28.83" end="00:00:29.02">the </span>
        <span begin="00:00:29.02" end="00:00:30.02">rain</span>
        <span ttm:role="x-bg">
            <span begin="00:00:29.26" end="00:00:30.02">(Ah)</span>
        </span>
      </p>
      <p begin="00:00:30.02" end="00:00:33.41" ttm:agent="v1">
        <span begin="00:00:30.02" end="00:00:30.42">She </span>
        <span begin="00:00:30.42" end="00:00:30.62">shares </span>
        <span begin="00:00:30.62" end="00:00:30.83">a </span>
        <span begin="00:00:30.83" end="00:00:31.41">room </span>
        <span begin="00:00:31.41" end="00:00:31.62">with </span>
        <span begin="00:00:31.62" end="00:00:31.82">her </span>
        <span begin="00:00:31.82" end="00:00:32.61">younger </span>
        <span begin="00:00:32.61" end="00:00:33.41">brother</span>
      </p>
      <p begin="00:00:33.41" end="00:00:37.00" ttm:agent="v1">
        <span begin="00:00:33.41" end="00:00:34.01">Clothes </span>
        <span begin="00:00:34.01" end="00:00:34.81">secondhand </span>
        <span begin="00:00:34.81" end="00:00:35.00">from </span>
        <span begin="00:00:35.00" end="00:00:35.20">her </span>
        <span begin="00:00:35.20" end="00:00:35.60">best </span>
        <span begin="00:00:35.60" end="00:00:36.00">friend's </span>
        <span begin="00:00:36.00" end="00:00:37.00">mother</span>
      </p>
      <p begin="00:00:37.00" end="00:00:40.31" ttm:agent="v1">
        <span begin="00:00:37.00" end="00:00:37.20">Cut </span>
        <span begin="00:00:37.20" end="00:00:37.40">'em </span>
        <span begin="00:00:37.40" end="00:00:37.80">all </span>
        <span begin="00:00:37.80" end="00:00:38.19">up, </span>
        <span begin="00:00:38.19" end="00:00:38.59">yeah, </span>
        <span begin="00:00:38.59" end="00:00:38.79">she </span>
        <span begin="00:00:38.79" end="00:00:38.98">got </span>
        <span begin="00:00:38.98" end="00:00:39.19">her </span>
        <span begin="00:00:39.19" end="00:00:39.39">own </span>
        <span begin="00:00:39.39" end="00:00:40.31">style</span>
      </p>
      <p begin="00:00:40.31" end="00:00:44.17" ttm:agent="v1">
        <span begin="00:00:40.31" end="00:00:40.84">Madonna </span>
        <span begin="00:00:40.84" end="00:00:40.99">on </span>
        <span begin="00:00:40.99" end="00:00:41.20">the </span>
        <span begin="00:00:41.20" end="00:00:41.58">wall </span>
        <span begin="00:00:41.58" end="00:00:41.78">next </span>
        <span begin="00:00:41.78" end="00:00:42.18">to </span>
        <span begin="00:00:42.18" end="00:00:42.78">Destiny's </span>
        <span begin="00:00:42.78" end="00:00:44.17">Child</span>
      </p>
      <p begin="00:00:44.17" end="00:00:47.20" ttm:agent="v1">
        <span begin="00:00:44.17" end="00:00:44.36">And </span>
        <span begin="00:00:44.36" end="00:00:44.57">she's </span>
        <span begin="00:00:44.57" end="00:00:45.17">all </span>
        <span begin="00:00:45.17" end="00:00:46.56">that</span>
        <span ttm:role="x-bg">
            <span begin="00:00:45.93" end="00:00:47.20">(Eh-eh-eh-eh)</span>
        </span>
      </p><
      <p begin="00:00:46.56" end="00:00:50.94" ttm:agent="v1">
        <span begin="00:00:46.56" end="00:00:46.96">'Cause </span>
        <span begin="00:00:46.96" end="00:00:47.16">she </span>
        <span begin="00:00:47.16" end="00:00:47.56">knows </span>
        <span begin="00:00:47.56" end="00:00:47.86">she's </span>
        <span begin="00:00:47.96" end="00:00:48.35">beau</span>
        <span begin="00:00:48.35" end="00:00:48.64">ti</span>
        <span begin="00:00:48.64" end="00:00:49.50">ful</span>
        <span ttm:role="x-bg">
            <span begin="00:00:49.98" end="00:00:50.94">(Ah-ah)</span>
        </span>
      </p>
      <p begin="00:00:50.94" end="00:00:54.05" ttm:agent="v1">
        <span begin="00:00:50.94" end="00:00:51.15">And </span>
        <span begin="00:00:51.15" end="00:00:51.34">she's </span>
        <span begin="00:00:51.34" end="00:00:51.93">taught </span>
        <span begin="00:00:51.93" end="00:00:53.53">that</span>
        <span ttm:role="x-bg">
            <span begin="00:00:52.78" end="00:00:54.05">(Eh-eh-eh-eh)</span>
        </span>
      </p>
      <p begin="00:00:53.53" end="00:00:56.32" ttm:agent="v1">
        <span begin="00:00:53.53" end="00:00:53.73">Her </span>
        <span begin="00:00:53.73" end="00:00:54.53">dreams </span>
        <span begin="00:00:54.53" end="00:00:54.73">don't </span>
        <span begin="00:00:54.73" end="00:00:54.92">live </span>
        <span begin="00:00:54.92" end="00:00:55.22">at </span>
        <span begin="00:00:55.33" end="00:00:56.32">home</span>
      </p>
    </div>
  </body>
</tt>
```
A perfectly clean and organized ``.ttml`` file for you in less than a second.

#### ***You've made it, you created your own TTML!***

