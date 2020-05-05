# webkitspeechrecognition
Simple experiment with webkitSpeechRecognition to check how it works. All you need is browser ( Chr***e, i had v.81 ).

Goal behind the experiment:
Ability to detect and mark "red" words in text.

Possible projects:
Teach kids to read. Kids reading 'books' by them self and get's interactions / achievments and other cool stuff, which will promote them to read more.

I tried the 'tool' on my kid, and here are some results:
- Kid got interactive... and wanted to read by himself, but...
- Kids voice, isn't that understandable by AI as aduls one ( some times it required like 5 times to 'hear' the voice )
- webkitSpeechRecognition buffers all 'translations' from speech and hold them. Continueing use of same session triggered laggings and miss understading from AI. ( stop() / start() did it's job )




How to use:
1. Change language of local. `recognition.lang = 'lt-LT';` Line - #72
2. Change text inside `#text_to_read` #59
3. 119 - 135 lines hold special symbols transformers. ( removes special symbols from both sides. For kids it's enough just to read... )
4. Done. Run the html in browser ( you even don't need server for it ).
