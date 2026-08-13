# In2STEM Project Presentation Helper

Use this guide to plan a short presentation about your galaxy project. Your aim is not to explain every line of code. Your aim is to tell a clear science story:

> What did we measure, how did we measure it, what did we find, and what might it mean?

## Suggested Presentation Structure

### Slide 1: Title

Include:

- your project title;
- your names;
- one image, plot, or visual connected to galaxies;
- a short subtitle saying what you investigated.

Example title:

```text
Measuring Star Formation in DESI Galaxies
```

### Slide 2: The Big Science Question

Explain the question your project is trying to answer.

Useful prompts:

- How quickly are these galaxies forming stars?
- Do more massive galaxies form more stars?
- Do the galaxies lie on the star-forming main sequence?

Keep this slide simple. One clear question is better than five vague ones.

### Slide 3: The Data

Explain what data you used.

Include:

- that the data comes from DESI galaxy observations;
- what a galaxy spectrum is;
- which columns you used, such as redshift, H-alpha flux, Balmer decrement, and stellar mass;
- how many galaxies were in the teaching sample.

Things to research:

- What is DESI?
- What is a galaxy spectrum?
- What does redshift tell us?

### Slide 4: Why H-alpha Traces Star Formation

Explain why the H-alpha emission line is useful.

Key idea:

Young, massive stars ionise gas around them. That gas emits light at specific wavelengths, including H-alpha. Stronger H-alpha emission usually means more recent star formation.

Things to research:

- What is an emission line?
- Why do young stars produce ionised gas?
- Why is H-alpha linked to recent star formation?

### Slide 5: Correcting for Dust

Explain why you corrected the H-alpha light.

Key idea:

Dust inside galaxies absorbs and scatters some of the light. If we ignore dust, we underestimate the true star formation rate.

Mention:

- the Balmer decrement;
- H-alpha and H-beta;
- attenuation.

Things to research:

- What is dust attenuation?
- What is the Balmer decrement?
- Why compare H-alpha and H-beta?

### Slide 6: From Flux to Luminosity to SFR

Show the steps of the calculation:

```text
observed H-alpha flux
        ↓
luminosity distance from redshift
        ↓
observed H-alpha luminosity
        ↓
dust-corrected luminosity
        ↓
star formation rate
```

Include one equation only if you can explain it in words. Do not fill the slide with equations you will not talk through.

Things to research:

- What is the difference between flux and luminosity?
- Why do we need distance to calculate luminosity?
- What are the units of star formation rate?

### Slide 7: Your SFR Results

Show your SFR histogram.

Say what the plot shows:

- What range of SFRs did you find?
- Are most galaxies forming stars quickly or slowly?
- Are there any extreme values?
- Are the mean and median similar or different?

Presentation tip:

Do not just say "this is a histogram." Say what the histogram tells you.

### Slide 8: The Star-Forming Main Sequence

Explain the main sequence idea.

Key idea:

Many star-forming galaxies follow a relationship between stellar mass and star formation rate. More massive galaxies often have higher star formation rates.

Things to research:

- What is the galaxy main sequence?
- Why is it useful for understanding galaxy evolution?
- What does it mean if a galaxy is above or below the main sequence?

### Slide 9: Main Sequence Plot

Show your plot of:

```text
log(SFR) against log(stellar mass)
```

You could show either:

- a scatter plot;
- a 2D histogram;
- both, if you can explain why each is useful.

Useful prompts:

- Is there a visible trend?
- Where are most galaxies concentrated?
- Why might a 2D histogram be easier to read than a scatter plot?

### Slide 10: Fitting a Relation

Explain the line you fitted:

```text
log(SFR) = gradient × log(stellar mass) + intercept
```

Do not worry about making the statistics sound complicated. Explain that the line is a simple model for the main trend.

Useful prompts:

- Is the gradient positive?
- What does a positive gradient mean physically?
- Does every galaxy lie exactly on the line?

### Slide 11: Classifying Galaxies

Explain how you classified galaxies:

- above the main sequence;
- on the main sequence;
- below the main sequence.

Mention that you used the difference between the observed log(SFR) and the expected log(SFR) from the fitted line.

Useful prompts:

- Which category had the most galaxies?
- What could cause a galaxy to be above the main sequence?
- What could cause a galaxy to be below the main sequence?

### Slide 12: Limitations

Good scientists talk about limitations. This makes your presentation stronger, not weaker.

Possible limitations:

- You used a reduced teaching sample, not the full DESI dataset.
- The fitted line is a simple straight line.
- Dust corrections can be uncertain.
- H-alpha traces recent star formation, not the whole history of the galaxy.
- Some measurements may have errors or unusual values.

Things to research:

- What is measurement uncertainty?
- Why might a simple model be useful even if it is not perfect?

### Slide 13: Conclusion

End with three clear takeaways.

Example:

```text
1. We used H-alpha emission to estimate star formation rates.
2. We found that SFR is linked to stellar mass.
3. We used a fitted main-sequence relation to classify galaxies.
```

Finish by returning to your original science question.

## What Makes a Good Science Presentation?

### Tell a Story

A good structure is:

```text
Question → Method → Results → Interpretation → Limitations → Conclusion
```

### Explain Your Plots

For every plot, answer:

- What is on the x-axis?
- What is on the y-axis?
- What does the colour or shading mean?
- What pattern should the audience notice?
- What does that pattern mean?

### Use Clear Slides

Good slides usually have:

- one main idea per slide;
- large text;
- labelled axes;
- readable plots;
- short bullet points, not paragraphs;
- enough contrast between text and background.

### Practise the Transitions

The best presentations feel connected. Try using sentences like:

```text
Now that we have calculated star formation rates, we can compare them to galaxy mass.
```

or:

```text
This plot suggests a trend, so next we fitted a simple relation.
```

## Questions You Might Be Asked

Prepare answers to these:

- Why did you use H-alpha to calculate SFR?
- Why did you need to correct for dust?
- What does log(SFR) mean?
- Why plot against stellar mass?
- What does the main sequence tell us?
- What does it mean for a galaxy to be above or below the main sequence?
- What would you do next if you had more time?

## Extra Research Ideas

If you want to understand the results more deeply, look up:

- DESI and why it observes millions of galaxies;
- galaxy spectra and emission lines;
- H-alpha as a star formation tracer;
- dust attenuation in galaxies;
- the Balmer decrement;
- stellar mass;
- galaxy quenching;
- starburst galaxies;
- the star-forming main sequence;
- why astronomers use logarithms.

## Final Checklist

Before presenting, check:

- every plot has clear axis labels;
- you can explain every plot in one or two sentences;
- you define SFR before using the abbreviation too much;
- your conclusion answers your original question;
- each person in the group has something meaningful to say;
- you have practised once out loud.
