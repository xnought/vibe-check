# vibe-check

Suppose I took every sentence you've ever said and computed the sentiment from -2 to 1.

-2 being the most negative, 0 as neutral, and 1 as the most positive. We interpret negative things as more important which is why the negative scale is larger.

If you average the score from everything you said, are you a positive or negative person?

What if it turned out that your score was very negative? Would this change how you interact with others?

This is a literal vibe check.

## Check others

You feel terrible based on interacting with someone? You ask, is it me?

Vibe check'em! Take everything they said and actually figure out if they happen to be a person that spews out negativity.

Then you can choose to weigh their opinions differently knowing that this is the way they are.

## Check yoself

Check your pattens. Could you phrase your life differently? Vibe check your interactions online or in the real world! See where you end up. Maybe change yourself for the better.

You have a fixed amount of time before nothingness. Try not to end up negative on this scale.

Pass the vibe check. (I understand how stupid this sounds, just go with it)

## Usage

```python
import gpt_vibecheck from from vibecheck

others_sentences = ["I hate you", "I love that I hate you", "I love you"]
your_personality = "I am a computer science student that dislikes unnecessary complexity and takes peoples suggestions too often. INTJ personality type."
vibe = gpt_vibecheck(
	personality=your_personality,
	sentences=others_sentences,
	open_ai_key="sk.xxxx...",
)
```

Outputs `-0.5666666666666668` as on average negative vibe. Maybe you should get more data on this person to be sure.
