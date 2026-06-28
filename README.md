While formality scoring has been applied to general text classification and fake news detection has been studied extensively on formal media datasets,
no existing work combines multi-feature formality-based epistemic risk scoring with WhatsApp-specific vernacular text, Indian language contexts, 
or a governance framework tied to existing regulatory authority. This project contributes with a structured seven-feature
annotation instrument calibrated for informal vernacular forwards.


The Seven Formality Features — Explained Simply
Think of these seven features as seven warning lights on a dashboard. Each one lights up when a message shows a specific sign of being unreliable or emotionally manipulative. Together they give you a full picture of how trustworthy a message is likely to be.

1. Source Attribution
Plain English: Does the message tell you where the information came from?
Reliable information almost always points back to a source — a name, an institution, a study, a document. Misinformation typically floats free of any origin because attaching a real source would make it verifiable and therefore falsifiable.
Low risk (source present):

"According to the Indian Council of Medical Research's guidelines published on 12 March 2024, the recommended daily water intake is..."

High risk (no source):

"Doctors have confirmed that drinking hot water cures this completely. Share with everyone."

Notice "doctors" in the second example is not a source — it is a vague appeal to unnamed authority. Real attribution names a specific person, institution, or document.
The deceptive middle case to watch for:

"A WhatsApp doctor group is saying..."

This sounds like a source but is untraceable. Label it high risk.

2. Epistemic Hedging
Plain English: Does the message acknowledge uncertainty, or does it present everything as absolute fact?
"Epistemic" simply means relating to knowledge and how certain we are of it. Legitimate reporting and scientific communication almost always includes hedging language — words that signal the limits of what is known. Misinformation tends to speak in certainties because doubt would weaken the emotional impact.
Low risk (hedging present):

"Early findings suggest a possible link, though researchers caution that more data is needed before any conclusions can be drawn."

High risk (no hedging):

"This is 100% proven. Scientists have confirmed it. There is no debate."

More hedging phrases that signal low risk:

"reportedly," "according to preliminary data," "it is unclear whether," "some experts believe," "this has not yet been independently verified"

The paradox to understand: The more certain a WhatsApp message sounds, the more suspicious you should be. Real knowledge is almost always partial and conditional. Absolute certainty in a forward is itself a red flag.

3. Emotional Superlatives
Plain English: Does the message use extreme emotional language to provoke a strong feeling — fear, outrage, urgency, shock?
Emotional superlatives are words and phrases at the extreme end of the emotional register. They are designed to bypass rational evaluation and trigger a share reflex before the reader has time to think critically.
Low risk:

"There has been an increase in reported cases in the district over the past month."

High risk:

"DEVASTATING news. The most HORRIFYING thing is happening RIGHT NOW and the government is HIDING it from you. This is CATASTROPHIC."

Common emotional superlative patterns:

Capitalised words: SHOCKING, EXPOSED, HIDDEN, SECRET
Intensifiers stacked together: "absolutely terrible," "completely devastating," "utterly shocking"
Urgency words: "right now," "before it's too late," "this moment"
Fear triggers: "your family is at risk," "they are coming for your children"

Why it matters: These words are not random. They are specifically chosen because they short-circuit scepticism. Recognising them is the first step to not being moved by them.

4. De-personalisation
Plain English: Is the writing impersonal and professional, or is it full of personal pronouns, personal stories, and first-person narration?
Formal, reliable communication tends to keep the author out of the text. It focuses on evidence and events, not on the narrator's personal experience. Misinformation often travels through personal testimony — "I personally know someone who..." — because personal stories feel emotionally real even when they cannot be verified.
Low risk (de-personalised):

"Hospital admissions in the region increased by 14% over the previous quarter, according to state health data."

High risk (highly personalised):

"My cousin's friend is a nurse and she personally saw this happen. She told my uncle directly. I am sharing because I care about all of you."

Why personal stories spread so easily: They feel trustworthy because they mimic how we share news with people we love. But in a WhatsApp forward, you have no way to verify the chain — cousin's friend's nurse could be fictional or composite.
Ambiguous case: First-person writing is not automatically high risk. "I went to the press conference and heard the minister say X" is personal but verifiable. What makes something high risk is the untraceable personal chain combined with no other evidence.

5. Passive Voice
Plain English: Does the message hide who is doing the action?
Passive voice removes the actor from the sentence. "Mistakes were made" instead of "The government made mistakes." In formal writing, passive voice is used deliberately to focus on outcomes over actors. In misinformation, it is used to make unverified claims sound official while avoiding accountability — because if you never name who did something, no one can check.
Low risk (active, transparent):

"The Ministry of Health announced on Tuesday that Dr Ramesh Kumar will lead the new task force."

High risk (passive, actor-hidden):

"It has been confirmed that vaccines are being used to insert tracking devices. This has been known for years but is being suppressed."

Notice: confirmed by whom? Known by whom? Suppressed by whom? Passive voice allows these questions to never arise.
The subtle version:

"Studies have shown..." (which studies?), "It is widely believed..." (by whom?), "Reports indicate..." (whose reports?)

These are passive constructions designed to sound authoritative while remaining completely unverifiable.

6. Exclamation Density
Plain English: How many exclamation marks are in the message?
This is the most mechanical of the seven features — you can count it directly. A single exclamation mark in a long message is unremarkable. Multiple exclamation marks per sentence is a strong signal of emotional manipulation or low-quality content.
Low risk:

"The board meeting has been rescheduled to Friday. Please confirm your attendance."

High risk:

"Wake up!!! They are poisoning the water supply!!! Share this NOW before it gets deleted!!! Your children's lives depend on it!!!"

Why this works as a signal: Professional communicators — journalists, doctors, researchers, government bodies — almost never use multiple consecutive exclamation marks. The exclamation mark density of a message is inversely correlated with its production context. The more exclamation marks, the less likely it was produced by someone with editorial standards.
Counting rule for annotation: Score 0 if there are 0–1 exclamation marks in the full message. Score 1 if there are 2 or more, especially if clustered together or used after every sentence.

7. Label Language
Plain English: Does the message use dramatic category labels to frame its content before you've even read it?
Label language is the set of words that pre-categorise a message as extraordinary, forbidden, or urgent — before any evidence is presented. Words like BREAKING, EXPOSED, SECRET, ALERT, URGENT, BANNED, CENSORED, LEAKED. These words instruct you how to feel about the content before you evaluate it.
Low risk:

"New findings on air quality in urban areas have been published in Environmental Health."

High risk:

"🚨 BREAKING ALERT 🚨 SECRET GOVERNMENT DOCUMENT LEAKED — What they don't want you to know. SHARE BEFORE THIS GETS REMOVED."

Why label language is particularly dangerous: It exploits the human tendency to pay more attention to things labelled as rare or forbidden. "BANNED" makes something seem more credible, not less. "LEAKED" implies insider knowledge. "CENSORED" implies the message is dangerous to the powerful — which makes the reader feel brave for reading it. All of these are emotional levers with no epistemic content.

Why These Seven Specifically?
These features were not chosen arbitrarily. They represent the intersection of three bodies of existing research:
Linguistics and discourse analysis — scholars like Biber (1988) developed formal registers precisely around features like source attribution, hedging, and passive voice as markers of institutional, accountable communication. High-formality writing uses these features heavily. Low-formality viral content avoids them.
Misinformation research — studies of viral false content consistently find that emotional arousal, urgency, and social proof (personal testimony) are the primary drivers of sharing behaviour, not belief in truth. Pennycook and Rand (2019) showed that people share misinformation not because they believe it but because they are not thinking carefully — and emotional language suppresses careful thinking.
NLP measurability — crucially, these seven features can be detected computationally. You can count exclamation marks. You can detect hedge words with a lexicon. You can classify passive voice with a parser. Source attribution can be proxied by proper nouns and citation patterns. This is why they are selected over more complex features — they are both theoretically grounded and technically tractable.
Together, they cover the full spectrum from structural (passive voice, source attribution) to lexical (emotional superlatives, label language) to punctuation-based (exclamation density) — giving the model diverse signal types to learn from.
