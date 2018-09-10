Comments from Albert de Roeck

Thanks for your analysis and paper on the measurements of the WZ production
and search for new physics

The analysis looks fine.
The paper is reasonably well written but there are some oddities here and there
as I will mention below :)

A few general comments:
-  We constantly refer to RIVET as a tool used for certain comparisons.
   Is the fact that we use RIVET really important for the results? Ie does it
   possibly affect the outcome of the numbers (as usually tools like MCs that we use, do and
   therefore we list them). If it does influence the final numbers then but is justified
   to name it explicitly every time. If not, it looks like a commercial at best or a
   broken record at worst. :)
   It would then be sufficient to mention it
   just once in the paper (for there benefit of the stakeholders), but it needs a
   reference, which I do not see right now (and which is much more important to the
   stakeholders tan anything else)

The fact that RIVET is used is relevant in the interpretation of the results in the sense
that it defines a common algorithm, with choices made in how dressed leptons, jets etc
are defined. We intend only to emphasize this, though we agree that the wording was combuersome.
It has been reformulated, and the reference has been moved into the main body of the text.

**TODO: Reword text to make Rivet mentioning more natural.**
**TODO: Add RIVET Citation in main body of text.**

- what did we do with taus in this analysis? If they the electrons and muons from the
   decaying taus are within the acceptance, are these considered signal or background?
   Be specific from the start please.

They are not explicitly vetoed, though they are not included in the fiducial cross 
section. Added clarification in text.

**TODO: Clarify treatment of taus**


Details
- line 4 Sloppy: Higgs mechanism -&gt; BEH or Brout-Englert-Higgs mechanism

- line 84: "...initial state bs not included": is that an issue for the analysis?
   How does it affective analysis, if at all?

- line 91: Do we depend on the merging scale? We should not. Was this checked and or
    a systematics for that included? I did not see that later.
    (but I expect almost no effect and would not even give the 27 GeV here)

- line 92: This looks a bit strange: comparing a NLO with a LO prediction to assess
    the modelling uncertainty. What did you check and what did you conclude?
    I assume this connected with the discussion at line 276?

- line 98 "with THE dynamic"

- line 103 "...for identical configurations" What do you mean here? Event topologies?
    Please say exactly what is meant.

- line 104: I recommend to start this paragraph with a list the main backgrounds

- line 110-111 "k-Factors" -&gt; K-factors" as most generally used.

- line 129: "27 pile -up interactions". Possibly the correct number but in recent
    CWR papers I have seen everything between 20 to 27 pile-up numbers quoted  for the
    same data set. I recommend to put the '27' only if this is the agreed number upon
    for all our papers on 2016 data set analyses.

- section 4: We should also say very briefly how we reconstruct neutral hadrons and
   photons with the PF algorithm as we eg use these in the isolation requirements.

- line 178: These are very precise numbers for the isolation selection on the
    leptons (3 significant digits). This begs the question on how these cuts
    have been tuned or optimised... Information to be added.

- line 184: So I understand here that we did not exclude the transition region
   between barrel and endcap in the ECAL, correct? Do we control the data/MC difference of the
   efficiency there well enough?

- line 209: affect -&gt; effect

- line 217 -2.5   The 'minus' is a bit poor. Maybe put &minus; or give |eta|&lt; 2.5

- line 248: See line 135:  in this paper we define and use pTMiss and NOT ETmiss!
    Also this has become the common practice in all our papers.
    However as of here we start using ETMiss in the text. Please change all these to
    pTMiss.

- line 267-269. Not easy to understand for the reader as the introduction to 2D
   comes only later in the paper.

- line 276: FxFx merging is typically used for NLO samples (dono if it
   works also consistently with LO generations), rather than for LO samples
   So what are we exactly doing here? Are we mixing LO with NLO?
   Just to make sure we do not something illegal that we could get criticised for
   easily..

- line 279: "generally seen to be within..." Is that an observation you made with
   studies in this analysis? Then I would rather say "generally found to be within..."   

- line 282: so what do we use this sample for? Do we find that the POWHEG agrees with the
    MC studies that we use? We should say something here.

- line 286: "for fixed and dynamic scale". Say here what scale you mean.

- line 294: This statement may well be right but as a reader (or referee) I would
    wonder on what this assessment is based, and if these contributions would not
    risk to be larger. Please elaborate or say where you got that information
    (you can blame it on a theorist if you want.)

- line 330: what is the value the modifier that comes out of the fit?
     We should give that information as well..

- line 338 : interference is negligible. How small is it (eg in % contribution)?

- line 366-369: what is the conclusion on this result? Consistent with SM expectation..?
     We should at least say something

- line 400 say here or somewhere nearby that we do not observe a deviation...

- line 407: What is meant precisely here? Contribution to what? too compact as is now...

- line 433: We could give a few more details/numbers here on previous results
   to substantiate this concluding  comment

<br />%ENDTWISTY%

---++ Comments from University of Virginia IR

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%

This paper is well written and addresses several topics including the production cross section for pp production of WZ at s =13 TeV and a further attempt to separate this production in into QCD and electroweak components.  The authors also attempt to determine how much of the electroweak cross section arises for BSM effects due to deviation of EW cross section from the SM expectation due to anomalous quartic gauge coupling or processes in which charged Higgs are produced and decay into WZ.

The following comments are suggestions to make the paper more readable.

A type comments

Figure 6 caption:  The arraignment of the figures are side by side so in referring to them in the caption, the language shodulbe changed from top -&gt; left and bottom -&gt; right.

B type comments

L70 the event rate -&gt; first level event rate

L143-145  The description of the treatment of bremsstrahlung along the electron tract is too terse.  Either a reference to the treatment or more description of how the brem is treated would help.

L170-179  The pileup is treated quite differently for electrons and muons in determining the isolation of the lepton.  For the reader a sentence or two about why this is the case would be useful.

L208   Please add a sentence about what problem is generated in the theoretic calculation by collinear emission of same flavor opposite sign dileptons or a reference to a discussion of the problem.

L245 and 251  The tight to loose “transfer factors” that transfer background events into the signal region are quite mysterious.  Please add some information about what these are and how they are determined

(even though the authors give a reference to the technique, the process is so minimally described it forces the reader to go to the reference).

L257   Choose a different adjective than “fakeable”.  This is an unclear descriptor.

L269  2D discriminant is referenced here although it is not defined until line 354.

L278  The MLN merging is mentioned earlier with a reference but a FxFx merged sample is mentioned with no discussion of what this sample is.

L284  A short description of what is meant by the RIVET framework is needed event if a reference is given.

Figures 2 and 3  The electroweak components are not at all evident in the two figures partially because of the choice of indicator symbol.  A

Different choice would make what this component is clearer.  As is

It is obscured by the cross hatching of the statistical + systematic errors.

<br />%ENDTWISTY%

---++ Comments from Greg Landsberg

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%

Congratulations on a new measurement of the EW WZ production and a well-written paper! Please, find my detailed comments below, arranged in the physics and style categories. My main concern is that while we may be able to publish this before ATLAS, their analysis appears to be much superior to ours, so the impact of the measurement part of this paper is going to be rather limited, unless some obvious possible improvements to the analysis are considered. 

One possibility to handle this is to really make the limits on the charged Higgs boson and the aQGC the main theme of this paper, rather than the cross section measurement at a not very impressive 2 s.d. level. ATLAS paper lacks these two interpretations, so one could make ours significantly stronger if we reorder the paper to emphasize these two components, which set the best limits to date.

PHYSICS COMMENTS:

- General comment: given that ATLAS is about to submit their WZjj observation in the very same channel and the same integrated luminosity, I wonder why the sensitivity of our analysis is so much lower than that of ATLAS. I'm not talking here about the giant fluctuation they seem to observe (5.6 s.d. observed with 3.3 s.d. expected, ATLAS-CONF-2018-033), but the comparison of 3.3 s.d. and 2.7 s.d. of the two analyses, which corresponds to about (3.3/2.7)^2, or 50% more effective integrated luminosity ATLAS gains over us. Clearly the fact that ATLAS uses BDTs, while this analysis only considers rectangular cutoff must contribute a lot, but also ATLAS is using the mT variable, while our analysis relies on pmissT to identify the leptonically decaying W, which must be suboptimal. Why are we not using the MVA approach for this crucial LHC measurement? I'm afraid that without analysis improvements, the lifetime of this paper will be the delta t between our and ATLAS submission, i.e. a few weeks at most. As soon as ATLAS paper is submitted, I doubt we will get many citation out of a similar analysis but with appreciably worse sensitivity. If ATLAS manages to submit before us, the paper will have even less of an impact.

- General comment: nowhere in the paper I see an investigation of the ECAL prefiring effect on your trigger efficiency. Given the forward energetic jets used in the analysis, it may be significant (10\% or so), which may be one of the causes of a somewhat lower cross section you measure. Has this been looked for, and if so, why it is not addressed in the paper? If the effect hasn't been considered, it must be included before the analysis can be published.

- General comment: most of the papers we publish with the fiducial cross section measurements provide the unfolded measurements. Why is the unfolding not performed in this analysis? Granted, the effect of unfolding on the lepton is fairly small; on the other hand, your fiducial regions are rather complicated and include pmissT, pjT, and mj] selections, all of which are considerably affected by the JES/JER, particularly given that the jets are in the forward region where the corresponding uncertainty are relatively large. I believe the fiducial cross section measurements should be done with unfolded data. Note that the ATLAS result uses unfolded data, naturally.

- L3: add the second standard reference ["long" paper] to the CMS Higgs boson discovery.

- L13: Ref. [6] is the CMS paper; you must've meant Ref. [4].

- L16: there is only one particular quartic coupling you really probe here, WWZZ; please say so explicitly.

- Figure 1: in the diagrams (a), (c), (d), you should explicitly put W± and Z along the two bosons emitted by the quarks. If you put W± on top, the lower outgoing quark should be the same as the corresponding incoming quark, but it must be changed to an antiquark q¯ in order to conserve electric charge. Since the two incoming quarks do not have to be of the same type, suggest labeling the upper two quarks as q' and q", while keeping the two at the bottom as q. The diagram (b) as shown, violates electric charge conservation; you should replace q¯ with q¯&#8242; and also mark the internal quark lines as q, q', q¯&#8242; (top to bottom).

- LL26-31: this paragraph really breaks the flow of the text; suggest moving it after the one ending on L37.

- LL34-36: We study ... in terms of the generalized framework of dimension-eight effective field theory (EFT) operators and charged Higgs bosons, as shown in Figs. 1 (c) and (d), and place limits on the corresponding couplings and production cross sections, respectively.

- L85: as the name suggests; VBFNLO is an NLO, not LO generator: "... from the generator {\sc vbfnlo} v?.? [16] at next-to-leading order (NLO) ... [also add the VBFNLO version number].

- L86: give the order of simulations with Sherpa: 18], at LO, and with fixed-order [note a hyphen!] calculations ... [Finally, give MoCaNLO+Recola version number here.]

- LL89-90: the description is very confusing. By "up to three outgoing partons at Born level" do you mean "up to one additional parton" [as W and Z are two outgoing partons], or do you really mean up to three additional jets emitted in addition to two gluon jets? You really should be talking about "additional partons" compared to the Born-level diagram in Fig. 1 (b) to avoid confusion: "... simulated at LO with up to ? additional partons included in the matrix element calculations with ...".

- L93: similarly, here you should say: "... with up to one additional parton in the matrix element calculations, and an inclusive ...".

- L94: give a version number of Powheg (v1.0 ?) here and the corresponding references; also give a reference to the MLM merging procedure.

- L101: please explain what is meant by "events drawn from the interference term only". Most of the calculations become non-renormalizabel if a particular term in the amplitude is taken out, which means that numerically they give garbage. Only full set of amplitudes guarantees a numerically stable and finite answer. The only way to assess the effect of interference is really to take the full calculation with the interference and subtract from it the two processes generated separately. Is this what's being done? Please, expand on this point in the paper.

- LL110,111: first of all drop "scaling" in both places, as "factor" implies "scaling"; second, per CMS Style, the correct usage is "K factor", so the two lines in question should say, respectively, "(K factor of 1.1)" and "(K factor of 1.7)".

- L121: since a single version fo Sherpa is used, drop the version here.

- L129: the average pileup in 2016 data was 23, not 27. The number 27 is from online plots, which are made assuming different total inelastic cross section as used in the offline measurement.

- LL131-132: as powerful as it is, the PF algorithm can't really reconstruct "each individual particle" in an event; please switch to the current PubComm-recommended: "... (PF) algorithm [39] that aims to reconstruct and identify each individual particle in an event with ...".

- L166: ... for light-quark and gluon jets.

- L173: since you use "j" to denote a jet, use: "... pjT/Aj for all pileup kets in an event."

- L204: m&#8467;&#8467; should really be m&#8467;&#8242;&#8467;&#8242; throughout the paper, as you defined &#8467;&#8242; as the leptons front he Z boson decay.

- L215 and multiple further places in the text: since you [correctly] use Roman "j" to denote jet starting on L20, you should use Roman "j" in all subsequent places in the paper, e.g., mjj, &#951;j1, etc. There are too many occurrences of this, which you should replace using context search throughout the paper.

- Table 1: the variables used in the first column often have not been introduced or have been called differently. In particular, suggest using p&#8467;&#8242;1T, p&#8467;&#8242;2T, p&#8467;T for the first three entries, |&#951;&#956;| and |&#951;e| [note Roman "e"] for the following two; |m&#8467;&#8242;&#8467;&#8242;&#8722;mZ| for the next one; m&#8467;&#8467; should read m&#8467;&#8242;&#8467;&#8242;; |&#951;(j)| and pT(j) should be |&#951;j and pjT; finally, use nb&#8722;jet [hyphen, not an en-dash]. Furthermore, I have a question on the fiducial requirements: for some of the variables, namely p&#8467;&#8242;1T, &#951;&#956;, they are looser than the EW signal selection used to make the measurement. How can you define the fiducial volume that goes beyond the range of your selection? That defeats the purpose of fiducial cross section, which doesn't rely on simulation to extrapolate beyond the measurement phase space! I urge you to redefine the fiducial selections by replacing 2.5 with 2.4 on muon pseudorapiditiy and by tightening the loose fiducial selection on the first lepton pT from the Z boson decay to 25 GeV.

- LL268-269: the sentence is completely unintelligible. What is "2D discriminant", which has never been mentioned before? What is the range 5--25\%, given that in the very previous line you claim that this contribution is 9\%? What "It" refers to? Are you trying to say that while on average the QCD WZ process acceptance is 9\%, it varies between 5--25\% as a function of some variable? Then say so in plain English and define this variable properly! This sentence needs to be either removed or completely rewritten.

- L271-272: ... uncertainties in the respective predictions and by comparing them with the predictions from alternative matrix element and parton shower generators.

- L273 and further in the text: the only QCD scale is &#923;QCD; what you call "QCD scales" are renormalization and factorization scales of the QCD RGE evolution, which goes beyond the level of details you need to give. Please either refer to them as "scale" or as "renormalization and factorization scales" and do not use "QCD". On this line, say: "uncertainties from the renormalization and factorization scale choice".

- L273: you need to define the way PDF uncertainties are calculated not at the end of Section 7, but here, where it's first mentioned. You should also cite PDF4LHC Run 2 recommendations when you talk about NNPDF replicas.

- LL275-276: this is the first time you mention the FxFx merging scheme [for which you should provide the reference!], while you mention the MLM scheme in Section 3. I don't understand the statement you make here: MLM is used with LO calculations, while FxFx is used for NLO ones. It makes little sense to use FxFx scheme instead of the MLM one on LO samples. Please, explain clearly what exactly was done and why one should believe that it represents the uncertainty properly. Also, note that you should use hyphens in MLM-merged and FxFx =-merged.

- LL277-278: another incomprehensible sentence. What exactly is "acceptance into a signal region from the control region"? Please, rewrite the entire sentence in plain English and explain properly what you meant.

- L286: you only discussed the dynamic scales in Section 3. What are the fixed scales? Fixed to what?

- L288: ... uncertainty in the signal cross section prediction when performing the EW WZ signal strength measurement. [I believe here you meant the EW WZ signal strength measurement, not the significance measurement!]

- LL298-299: why would the uncertainties in the misidentification probability be uncorrelated between the channels. All channels with electrons should be affected by the electron misidentification probability uncertainty in a correlated way! Please, explain your assumption.

- Table 2: just to make sure, is the impact listed in the last column is really in the signal significance (i.e., the probability for the background only to fluctuate to or above the measured number of events) as the caption claims, or in the signal strength (&#956;)? These are not the same quantities.

- L325: the sentence sounds funny: why would one measure the cross section by fitting the expected event yield? This is a closure test, not a measurement. Please, drop "and expected".

- LL329,335,341,346-347,362,368: since several versions of MadGraph5_aMC@NLO are used in the analysis, it would be good to remind a reader which versions were used to obtain these predictions.

- L340: I think you meant to say: "The acceptance increase from the tight to loose ..."

- Figure 2: use "Dijet mass [GeV]" as the x axis caption on the left plot, to match the text; also remove the (a) and (b) labels below the figure.

- LL363, 365+4, and Eq. (3): use the same terminology, &#956;WZjj, here, as introduced on L330.

- L375: ...  charge conjugation and parity conserving ...

- Eq. (4): use p&#8407; T(W,Z) to denote vectors; define ET [note T in Roman].

- L383: technically speaking, the f&#57915;i parameters are not "couplings" but [Wilson] coefficients in the EFT operator expansion. Suggest to call them coefficients, and not couplings, throughout the paper.

- LL398-399: while it's clear from the comparison of Table 4 and Fig. 5, that the contours correspond to the 2D likelihood function quantiles [i.e., the intercepts of the ellipse with the axes correspond to a larger interval than the 1D limits quoted in Tavle 4], it won't hurt to state this explicitly in the text: "The resulting 2D 95\% CL limits ..."

- Figure 5: remove the (a) and (b) labels below the figures.

- Figure 6: sH [H in Roman] in the right pane y axis label. The right-hand-side plot could benefit from suppressing zero on the y axis and zooming on the interesting region in sH.
 

STYLE COMMENTS:

Title: suggest "of electroweak WZ boson production" and "in proton-proton" collisions;

Introduction:

L3: ATLAS and CMS Collaborations [1,2,2a] at the CERN LHC provides;

L5: to the Higgs field and;

L10: in proton-proton (pp) [note a hyphen, not an en-dash];

L11: ATLAS and CMS Collaborations and 7, 8, and 13 TeV [since ATLAS published earlier, it should be mentioned first];

L13: by the ATLAS Collaboration;

LL14-15: or via vector boson;

L18: forward, high-momentum jets;

L21: to the WZjj channel proceeds;

Fig. 1 caption, LL1-2: The EW-induced [can't start a sentence with an acronym]; L3: (b) via kinematic variables.

The CMS detector:

L56: resistive-plate chambers;

L73: eliminate a stray quotation mark at the end of the line;

Data and Monte Carlo samples:

L75: sample of pp collisions;

L79: leading order (LO);

L83: using {\sc MadSpin}.

LL98,99: &#956;R; &#956;F [R and F in Roman];

L99: mW [W in Roman, twice];

L100: mass, taken from Ref. [22].

L107: The production of ZZ pairs via;

L110: at next-to-NLO (NNLO) order [you use the acronym NNLO later in the text];

L113: via {\sc MadSpin}.

L123: as the corresponding hard scattering process.

Event reconstruction:

L131: a particle-flow (PF) algorithm [you use the acronym later];

L135: PF objects in an event.

L149: associated with small;

L155: algorithm [42] with a distance parameter R=0.4;

L162: between jets from hard scattering and from pileup interactions.

L165: b quark jets;

L166+3: <0.3 (0.4) around electron (muon) direction [follow the logic of the paper: electrons described before muons];

L183: about 85 (77)\% at peT&#8776;10 GeV to about 95 (89)\% for;

L187: The data-to-simulation efficiency ratios;

Event selection:

L202: the events are required to have pmissT>30 GeV.

LL213-214: with the second-highest pT;

L217: between &#8722;2.5 and +2.5. [Minus sign, not a hyphen.]

L220: the ``Higgs boson selection".

Table 1 caption, LL2-3: The EW signal selection; LL3-4: for charged Higgs boson search, which uses the selection; L6: to Born-level leptons;

Table 2 body, header line: ES signal; Higgs boson; Tight fiducial; Loose fiducial;

Background estimation:

L225: add a comma after "e.g." [US English];

LL228-229: are estimated from control samples in data. [Since data-driven is jargon!]

LL238-239: with the {\sc vbfnlo} prediction [50].

LL239-240: is further discussed in Section 7.

LL241-242: processes with nonprompt leptons are evaluated using control regions in data of events;

L245: ``tight-to-loose";

L252: with the tight-to-loose [no quotation marks and no italics];

LL257-258: is limited by the event count in control regions;

L260: in WZjj events.

L261: relaxing the jet pT requirement in WZ events;

Systematic uncertainties:

LL267-268: The uncertainty in the events acceptance for the EW signal selection;

L268: and 5\% for EW WZ processes.

L270: The uncertainties in the QCD WZ background and EW WZ signal;

L274: The uncertainty in the QCD-induced;

LL279-280: within the scale and PDF uncertainties;

L281: add a comm before "but";

L283: and QCD WZ processes interference is evaluated with particle-level simulated events;

L286: for both fixed and dynamic scales.

L290: uncertainty in the;

L291: Higher-order EW corrections to VBS processes;

L303: in both the EW signal and Higgs boson selections.

L304: in prompt backgrounds are;

L308: &#956;R/&#956;F&#8805;2. [F, R in Roman.]

L309: The PDF uncertainties;

Table 2 body, header line: &#963;WZjj [jj in Roman]; EW WZ signal significance; first columns: Nonprompt event count; b tagging; Integrated luminosity; second column: please typeset all the plus and minus signs in math mode; either replace the dash with N/A, or explain the dash in the caption.

L315: the b quark content;

L316: in the b tagging efficiency between data and simulation.

Fiducial Cross Section ...:

LL322-323: Fiducial cross section measurement and search for EW WZ production;

L328: EW- and QCD-induced;

L330: &#956;WZjj [jj in Roman];

L338: The interference term contribution;

L343: from the scale and PDF uncertainties;

L344: The scale uncertainty in the;

Fig. 2 caption, L8: uncertainties in the;

LL350,351: the EW- and QCD-induced;

Fig. 3 caption, L1: The one-dimensional representation of the 2D distribution of the dijet mass; L2: signal extraction. The x axis shows;

L365+2: local p value;

L366: uncertainty in the &#956;WZjj measurement;

Table 3 caption, L1: Post-fit event yields;

Table 3 body, header line: Total yield; first column: Pred. background; EW WZ signal;

Limits on anomalous quartic gauge couplings:

LL371,378: aQGCs;

L378: mixture of gauge and Higgs field interactions;

L383: coupling for the operator;

L387: coupling value, a parabolic;

LL390-391: put commas around "except for the coupling being probed";

Fig. 4 caption, L2: on the anomalous coupling parameters.

Fig. 5 caption, LL2-3: expected 68, 95, and 99\% CL limits (dashed contours) on; L3: confidence confidence levels.

Limits on Charged Higgs Production:

L401: Limits on charged Higgs boson production;

L402: charged Higgs bosons (H±) with;

LL408-409: Higgs boson selection;

L417: to be unity.

Summary:

L424: at the LHC in 2016.

Fig. 6 caption, L2: replace H+ with H± [also note H in Roman]; replace BR with &#57902;, as on L416; replace (top) with (left); L3: Georgi--Machacek [en-dash, not a hyphen] model (right)
.
L433: from either the WZ channel or from other channels.

References:

Ref. [5]: fix "(&#8730;s) in the title.

Ref. [22]: consider replacing with the just announced 2018 edition.

Ref. [34]: long published in Eur. Phys. J. C {\bf 76} (2016) 196; please add the journal and doi references.

Refs. [42,44]: these are identical references; please replace Ref. [44] with [42] in the paper on L161.

Ref. [46]: replace with the 2018 b tagging paper.

Ref. [56]: typeset the Erratum the same way you do the main references: [Erratum: {\it Eur. Phys. J. C\/} {\bf 73} (2013) 2501].

Refs. [54,55,59,60]: these are identical pairs of references; please replace Refs. [59.60] on L390 with [54,55].

<br/>%ENDTWISTY%

---++ Comments from Ohio State University IR

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%

This paper presents the first measurement of WZ electroweak vector boson scattering at 13 TeV. The cross section is sensitive to BSM physics and thus is certainly topical, although the data agrees well with the standard model. The text is complete and well written. The group is to be congratulated on completing in a timely manner this important result. It is important for this paper to be published without further delay. However, we do have a few specific comments:

 

Type B

L13: aQCG is defined here and a reference is given for a search result, however there is no clear reference to a description on what aQCG actually is. Is this description contained in reference [6], or is there another reference needed here?

L24-25, Figure 1: The distinguishing kinematic variables are described in lines 26-31, but readers (like myself) may ask "which variables?". Perhaps a rewording ("such as…") is warranted to avoid this confusion.

L28-29: The reader needs to read until roughly line 352 to have it explained *which* kinematic variables distinguish between QCD and EW productions; not all readers may understand this inherently and it would be useful to briefly explain which variables are involved and why they enhance EW over QCD.

L74, 94, 187, 310, 316: You should write “Monte Carlo simulation” or “MC simulation”, see the style guide.

L83: MadSpin needs a reference. Please check if this one is the latest: “P. Artoisenet, R. Frederix, O. Mattelaer, and R. Rietkerk, “Automatic spin-entangled decays of heavy resonances in Monte Carlo simulations”, JHEP 03 (2013) 015, doi:10.1007/JHEP03(2013)015, arXiv:1212.3460.”

L98: You haven’t yet defined “\pt” as the transverse momentum.

L137-139: "The physics objects are…" — It seems that this is taken from the PubComm recommendations (https://twiki.cern.ch/twiki/bin/viewauth/CMS/Internal/PubDetector) but the twiki has been updated at some point, and this sentence in the paper should be made to match.

L140, 146: \eta^{e} and \eta^{\mu} don't appear to be defined anywhere, and in this context it's not clear if these differ from the standard pseudo-rapidity.

L155: “R” should be defined as the distance parameter.

L157: You need to define \Delta R here, rather than in L166+, since this is the first place you use it.

L204: "there should be no" — more deterministic language should be used as you required this.

L214-6: Why are the high dijet mass and pseudorapidity separation typical of a VBS process? It would be good to briefly describe the unique VBS signature.

L234-9: We didn't follow how the data in the EW control region is used to constrain the background estimate that is taken from simulation. Can you clarify?

L265: "The major uncertainties" — 'major' is a subjective word and very inflammatory compared to 5-25%. "most significant" or "largest" would be more appropriate.

L276: What is the FxFx merged sample? You only mention it here.

L291-294: While it's understandable that an un-calculated correction hasn't been (can't be, really) applied, this paragraph does stand out in that "tens of percent" is of the order of most of your systematics to start with. If several "tens", then this is a very significant uncertainty on the signal yield and could potentially enhance the results quite a bit. Has there been any study on the effect of this? If the effect is considerable on the signal strength determination, it may be worth an additional sentence explaining the impact of its inclusion.

Table 2 caption: same comment on "major". If this is to be understood as "non-negligible" there must be better wordings for this, because ~10% is not what I would consider a "major uncertainty".

Table 2: Should be “Integrated luminosity”.

Figure 3: most of the error bars in the ratio are off-scale, and in some bins the central value is nearly so. The range should make the results clear, as this is a very important plot.

 

Type A

L33: Parallel construction — "or suggest" —> "or"; otherwise "or it could suggest", etc

L166+: Line numbers are missing for this paragraph.

L339: Should be “defined in Table 1 following Ref. [19]”.

L365+: Line numbers missing.

L426: “SM” needs to be redefined in the Summary section.

<br/>%ENDTWISTY%

 
---++ Comments from Kyungpook National University IR

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%


 The preprint is generally well-written and so do have minor things as below.  Please refer.


*** Type A comments

 

 

L17 : Vector boson scattering processes form a distinct experimental signature

-> VBS processes form a distinct experimental signature

 

L34-36 : please rearrange the sentence according to the figures, i.e.,

in terms of...., shown in Fig. 1 (c) and (d), -> in the generalized framework of dimension-eight effective field theory operator and in terms of charged Higgs boson, shown in Fig. 1 (c) and (d), respectively,

 

L48 : define pT here because of it appear for the first time, e.g.,

with 1 < pT < 10 GeV -> with the transverse momentum pT range of 1-10 GeV

(if so, L143-144: the transverse momentum, pT -> pT)

 

L73 : remove the symbol ' at the end

 

L92 : "NLO" -> "next-to-LO (NLO)“

 

L110 : "next-to-next-to-leading order" -> "next-to-NLO" or "next-to-NLO (NNLO)“

 

L155 : "PF" was not defined. so "particle-flow" -> "particle-flow (PF)" in L131.

 

L164 : its decay to b quarks -> its decay to b quark

 

Eq.1 : change comma to a period

Eq.3 : add a period

 

L248, L314 : "E^{miss}_{T}" -> "p^{miss}_{T}“

 

L330 ~ L332, L363 ~ L366 and other places : Throughout this paper, "signal strength modifier" and "signal strength" are used to refer mu. If the two are same meaning, please select one.

 

L351 : "The ratio of EW to QCD-induced production of WZjj grows .... in Fig.2 ... " There is no this ratio histogram in Fig.2. This sentence and Fig.2 doesn't match.

 

L372 : remove "(EFT)“

 

Figure 5. : This figure has 99% CL curve, but there is no explanation in the text nor in the caption.

 

Figure 6. : (top) --> left , (bottom) --> right

 

 

 

*** Type B comments

 

L23-25, L27-29 : Can you explain how the QCD-induced WZjj production can be EW-induced component via kinematic variables?

 

Introduction: You might summarized following sections in the end of this section.

 

L94 : specify a version and add a reference for POWHEG (one listed in L108?)

 

L127-129 : Can you put a reference for the average of number of pileup?

   

L155 : with R = 0.4 -> with a distance parameter of 0.4

 

L157 : define deltaR here (instead of defining in L166-167)

 

L212-220 : you consider the two leading pT jets and look for them passing the other Mjj and deta selections.

How many of those events contain more than one such dijet pair for signal and background, respectively?

Another question is what happens if you perform all possible dijet pairs with pT > 50 GeV and choose the pair that passes the selection criteria?

Can you choose the one with the highest value of m(jj) and compare to your results in this case?

Same questions to the Higgs signal selection.

 

L231 : could you explain why both components are excluded from the nonprompt estimation?

 

L276 : add a reference for the FxFx algorithm (e.g doi:10.1007/JHEP12(2012)061)

 

L406 and Figure 6. : There are two definitions of s_H. One is "the fraction of the contribution from the triplets to the W bosons" (L.406) and the other is "the vacuum expectation value ratio"(Figure 6.) If the two definitions are identical in GM model, then it woud be better to describe clear definition around L.406 and then Figure 6 doesn't need to define it again.

 

L411 : a small intrinsic width ==> how small ? for example, what % of m(H+-) ?

 

Table 3 : How you understand the discrepancy between predicted background events of 22.5 and observed events of only 15? It's more than 3 sigma deviation.


Question of ECAL prefiring:

There is a probability that a fraction of events since late 2016 data have been lost due to L1 ECAL endcap prefiring.

Did you take a look at the prefiring effect on forward jets with 2.25<|eta|<3.0 in 2016H on your analysis results?

<br/>%ENDTWISTY%

---++ Comments from University of Pavia IR

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%

We have only minor suggestions:

line 144 : too many commas : it's difficult to read . Better "transverse momentu pt and eta and on a categorization

line 148 : "minimal quality requirements" would it be possible to have a ref where "minimal" is defined ?

line 198-199 : " if more then one combination is possible" your choice doesn't make any bias on the sample? (It may be better to say how many cases they are)

line 284 : it could be better , if possible, to insert a ref. on RIVET ?

Summary : Results are very nice so it may be worth to spent some more writing on previous analysis comparison

<br/>%ENDTWISTY%


---++ Comments from DESY IR

%TWISTY{mode="div" showlink="Show comments and responses" hidelink="hide" showimgleft="%ICONURLPATH{toggleopen-small}%" hideimgleft="%ICONURLPATH{toggleclose-small}%" }%

General comments:
-----------------
- The paper describes an important measurement, congratulations.
  We appreciate the detailed analyses/interpretations in the context
  of the SM and BSM models.

- In general the focus of the paper could be more on the fiducial WZjj
  cross section measurement (seems to be the main result) and less on the
  EW WZ production.

- The paper has a nice introduction.

- Some parts of the paper are a bit difficult to follow (unavoidable?), in particular one could
  improve the clarity of
  - The description of the MC samples (section 3)
  - The description of signal and control regions and transfer factors and uncertainties for backgrounds (section 6)
  - The description of modeling systematics (section 7)
  More details will be provided below in TYPE B comments.

- There is excessive use of the term 'significance', (e.g. Table 2 and l.321 and l.355/356) which could be reduced.
  The purpose should always be to measure a physical quantity (e.g. signal strength of EWK WZjj production).
  The significance is just a tool to quantify an excess that is observed with respect to some null hypothesis.
  It is not an observable that we can measure.
  In addition, the null hypothesis for the different interpretations is not always clear.
  Especially in a paper where so many different interpretations are given it needs to be very clear what has been done.
  In the case of the EWK WZjj signal strength measurement, the null hypothesis is 'no EWK WZjj',
  which is not the same as the null hypothesis for the BSM interpretations
  (because the null hypothesis for BSM interpretations is 'SM' and that includes EWK WZjj)

- On the maximum likelhood fits and limit settings (section 8 and ff) there
  are some questions, e.g. which types of PDFs are used for nuisances parameters
  such as JES (e.g. log-normal?) Further questions and details below in TYPE B, section 8.
  We think that one needs to add some information here to the paper text in order to make
  the measurement reproduceable.

- For the extraction of the EW ZW cross section, why don't we also
  provide the information on the extracted QCD ZW cross section
  that seems to be fitted also?

- Given the separation that between EW-WZjj signal and the background
  sources, visible in Fig. 2 and 3 (e.g. last bin of the Di-jet Mass)
  the final expected significance is a bit disappointing.
  Is this because of limited MC Statistics or really
  because of the data statistics?

TYPE B:
-------

Title:
  --> 'Measurement of WZ production ..'
  Reason: it seems that the WZjj measurement is the main result of
  this paper and not the electroweak WZ production

Abstract:
  Suggest to have first the sentence
  "The total WZ plus two jet production cross ssection is measured in fiducial
  regions with enhanced contributions from.."
  and then "The cross section contribution from electroweak WZ production
  within this region is measured with an observed..."
  Reason: No significant excess is observed, so why not highlight the mu_(VBS)
  best-fit signal strength and uncertainties in the abstract instead?

>>>>>>>>> Section 1 <<<<<<<<
Fig.1: , is the diagram (a) really correct, isn't one of the q
  quarks ending as q and not q'?

l.26: What do the authors mean by "moderate missing transverse momentum"

l.28: 'These kinematic selections are used to distinguish the EW.. from
  ..QCD-induced process, which is considered as background'
  --> is this sentence really needed and does it make sense,
    for the total WZjj measurement QCD-induced process is signal..
    also it is not correct to say that these kin. selections are used to
    distinguish, because you separate the contributions within (and not with) the given kin. selection
    from distributions of observables in the region.

>>>>>>>>> Section 2 <<<<<<<<<
l.54-60: the detailed discussion of the muon system vs. eta and track pt resolutions.. where is
  this later relevant?

>>>>>>>>> Section 3 <<<<<<<<
 - The labels LO, NLO and NNLO are used extensively throughout this section,
   but they often mean different things, which can be very confusing.
   E.g., lines, 79, 90: 'simulated at LO ... with MADGRPH5_AMC@NLO'
   presumably means that the electroweak part has been simulated at LO,
   while the QCD part has been simulated at NLO?
   -> In general, clearly specify for each "XLO" label whether you refer
      to EW or to QCD.

l.81: 'resonant W boson propagator', perhaps a stupid question, but could there be
  also a 'resonant Z boson propagator'

l.84: 'Contributions with an initial state b quark are not included'
  Weird, why not?
  Please motivate.

l.91: why does one need to merge different jet multiplicities?

l.96:, how can the diagrams in Fig.1 (a) and (b) interfere, they have
  a different final state.
  Please give the reader an idea about the graphs which do interfere
  (citation?)

l.106: why use four-flavour scheme and scale to five-flavour scheme,
  why not using five-flavour scheme from the start?

l.110: 'calculated at NNLO for qqbar to ZZ ... and at NLO for gg->ZZ'
   This does not make sense. A qqbar initial state at NNLO (NNLO PDFS)
   means something different than a qqbar initial state at NLO (NLO PDFS).
   So here the two generated samples are not complementary to each other,
   since qqbar at NNLO is not complementary to gg at NLO.
   Furthermore, it is not stated what happens to the qg contribution,
   which is nonzero at NLO QCD (qg -> qqqbar -> qZ).
   Similarly, generating qqbar -> ZZ at NLO with POWHEG and gg->at LO
   with MCFM does not make sense (unless 'NLO' and 'LO' refer to the same
   order in alphas, and NLO PDFs are used in both cases). Again, what
   happens to the qg initial state, which contributes at NLO QCD?
   For a full nonoverlapping simulation all contributions have to be taken
   from the same order PDFs, with nonoverlapping matrix elements.
   The clean solution here would be to take everything from NLO QCD.

l.121: --> 'For all simulations used in this analysis the NNPDF3.0 [36] set ...'
  Reason: Otherwise it sounds as if you are just referring to the sim. mentioned
  on top of p.4

>>>>>>>>> Section 4 <<<<<<<<<
l.136-139: --> it is clear that charged tracks can be associated to a primary vertex candidate,
  but how can the associated pt_miss (as mentioned) and how can a jet be associated to a primary vertex?
  In particular the pt_miss I find confusing.

l.180-188:, is the rather detailed listing of eff. vs eta so crucial?

>>>>>>>>> Section 5 <<<<<<<<<
l.204: "no b tagged jet with pT>30 GeV and |eta|<4.7"
   Can we do b tagging up to |eta|=4.7 ?
   Very misleading. Quote the actual btag range (2.4?) instead?

l.207: 'chosen for event generation efficiency'
  is this a good argument? Perhaps just omit.

Table 1: content: is >20, >20 in the first two lines of the
  "loose fiducial" really intentional, or is it a typo?
  One can do this, but it is not obvious from the context why one would.
  If not a typo, specify why? (maybe compatibility with some external
  prediction?)

Table 1: what you call the first two columns one could call the second
  and third column.. I think it is better to write 'in the columns labelled "EW Signal"
  and "Higgs signal"... indicated in the column "Higgs Signal" .

Table 1: '.. applied to showered and hadronized events'  this sounds slang
--> 'applied to showered and hadronised simulated events'

>>>>>>>>> Section 6 <<<<<<<<<
- It should be described how the EW WZ process is evaluated as background for the aQGC and Higgs analyses,
  particularly for the later where the event selection is different.

l.227:  --> 'primarily ttbar and Z+jets'

l.229: 'the Z gamma process ...'
   You presumably mean 'the Z gamma(*) process'?
   I had to reread this sentence several times before I understood its
   intended meaning.

l.229-231:  Not clear. If I understood correctly one wants to say "... data-driven technique,
  except for the component of the Z&#947; process in which the photon experiences conversion into leptons in the tracker (non prompt).
  In such case, simulation is used.

par l.233-240: for the measurement of WZjj the QCD WZ production is signal.
  Here you treat is as background and do a normalisation using control regions.
  Is this consistent with the later extraction of WZjj and electroweak WZ cross section?
  Related comment: 'EW signal selection control region' sounds confusing (as if the signal selection is used to define a control region)
  when really it is a control region that is as close as possible to the EW signal selection, right?
  This could be clarified. In addition, it would probably  make sense to mention here already that this control region is included in the fit?

l.234: How is background from simulation constrained by the data? Normalisation? Shape?

l.241 in general when you use 'loose' selections as control regions
  which assumptions do you make on the composition of the event in
  these regions? e.g. neglect signal components? Are the events
  in the loose region statistically independent from the tight regions?
  Don't the loose regions contain the events in the tight regions,
  so they are correlated?

l.245: '"Tight-to-loose" transfer factors' isn't that '"Loose-to-tight'" transfer factors
 
par l.247-256: got completely lost here, find the description not understandable.
  you introduce many different samples: DY and ttbar, dijet events (l.251, how are they defined?)
  and Z+jet events.. in particular it is confusing that you start in l.247 with
  'This method is validated' and then in l.250' These results are cross-checked'
  I did not understand what was really checked with what and what you mean by 'These results'

par l.257-263: again got lost here. What do you mean by 'fakeable object control regions'??

l.259: 'nonprompt background, ..with the normalisation per channel
  taken from the ratios measured in WZ plus two jet events.' Isn't that interfering
  with your signal extraction for WZjj?? Is there a short-circuit here in the method?


>>>>>>>>> Section 7 <<<<<<<<<
- The theoretical uncertainties in the model dependent limits should also be discussed

l.266: start a new par at "The JES and JER ..."
  otherwise it looks like that this and the following sentences in the same paragraph should cover
  also the modeling uncertainties.

l.268: 'acceptance in', there is not 'acceptance into'

l.269: 2D discriminant was not yet introduced.

l.270: 'The modelling uncertainty'

l.270: 'on the QCD WZ process' ??? it is not always background!

par l.270-282: it is really hard to follow the description
  of the model uncertainties, what enters finally as uncertainties
  on shapes and on normalisations. Please try to improve clarity.

par l.283-290: also find this paragraph hard to understand/follow.

l.291-294: "Higher order EW corrections in VBS processes are known to be negative and at the level of tens
  of percent [51]. Such corrections have not been calculated for the final state considered in this
  paper, and therefore are not explicitly considered. It is, however, expected that the contribution
  of such corrections are within the theoretical uncertainties considered."
  - Would the correction really have an effect of 10s of percent? (so like 20% or 30%?)
  How large is the theoretical uncertainty assigned to try to cover this?

par l.295-303: could there be some double counting
  of statistical uncertainties also counted as systematical uncertainties?

l.308: what is a 'fit distribution'?

l.309: 'bin-by-bin' Why treating each bin as uncorrelated from the other here?
  Isn't that a fully bin-to-bin correlated sys. source?

l.310: is the uncertainty from the MC replica sets really a Gaussian uncertainty?
how is the width of the gaussian defined?

Table 2: --> 'freezing the set of associated nusiance parameters'

Table 2: how is the relative systematic uncertainty calculated? is it
  (nominal^2 - (uncert with set of NP's frozen)^2)/(nominal^2); sqrt(nominal^2-(uncert with set of NP's frozen^2))/nominal;
  or yet something else? On the effect on the significance: is the nuisance term actually removed from the fit,
  or is it frozen to its best-fit value? If it really is the former then the best-fit mu value can also change
  (if there are pulls on these parameters) and so this is not a fair comparison.
  It would be more insightful to use the relative uncertainty on mu_EWK calculated
  in the same fashion as for the fiducial WZjj cross section measurement.

l.321: 'uncertainty in the ... EW WZ significance measurement':
  there is no such thing as the measurement of a significance; the measurement is of the EW WZ signal strength,
  and after the measurement one can quantify the significance of the observed excess over the background-only expectation
  (hypothesis: no EW WZ production). Please rephrase


>>>>>>>>> Section 8 <<<<<<<<<
- What is the aim to define a looser fiducial region? Should be explained.
- On the maximum likelihood fit and confidence interval estimation in this and later
  sections we have several questions:
  - Do you use the Higgs combine tool? (for our internal knowledge)
  - Do you use in general a likelihood based on Poisson statistics or gaussian approximation?
  - Do you take the MC stat. uncertainties of MC templates into account with
    the Barlow Beeston method? Do you use gaussian approximation for these unc.?
  - Do you apply template morphing for nuisance parameters? (use
    +- 1 sigma variations and nominal template for interpolation
    and extrapolation of dependence of template on nuisance parameter, as
    done in combine tool)
  - What PDFs do you use for nuisance parameters such as JES: e.g. log-normaltype?
  - you seem to use the asymptotic (means large stat.) formulae from the Cowan paper [56].
    Are you sure these asymptotic formulae are valid? For some channels the stat.
    in some bins look close to zero events. Within the combine tool one can make cross
    checks using toy experiments.
  We would recommend to explicitly mention some of these things in the paper,
  for instance the types of PDFs for nuisance pars, to make the measurement
  reproduceable.

l.324-325: "The cross section for WZjj production is measured with a combined maximum likelihood fit
  to the observed and expected event yields".
  Rephrase:  The fit is not to the observed and expected event yields, but of the expected event yields
  to the observed event yields (assuming the four individual decay channels indeed include a single bin in the fit each).
  If the expected events yield have a statistical uncertainty than one is fitting
  the expected event yields to control data or to MC data (Barlow Beeston method). Is that what you are doing?

l.329: what are 'scaling nuisance parameters' this term seem to be not well defined.

Fig. 2: the stacking of the white empty area for the EW-WZjj looks
  not so nice.

Fig. 2: the hatched band, labeled "Stat. Unc." is not explained in
  the caption

Fig. 2: 'The solid symbols' not sure if I understand what you mean here.

Fig. 2: last line, the normalisations are not shown. --> 'The predicted yields
  are shown with their pre-fit normalisations.' or similar

l.353-355: "This motivates the use of ...for the extraction of the EW WZjj significance".
  Rephrase: for the measurement of the EW WZjj signal strength.

l.357: Is a distribution fitted in this control region too, or is the control region included as a counting experiment?

l.358: "The fit is performed independently for each channel"
  - if there are independent fits for each channel then for each channel a different muEWK should be quoted.
  Only one is given. So it looks more like a simultaneous fit of all the different channels.
  If there genuinely is one fit per channel, then the authors need to explain how they arrive at a single number at the end.

Fig. 3: Perhaps better to plot log-y scale, it is really hard to see in the linear y-scale
  the signal/background discrimination.

Fig. 3: 'The predictions are shown with using the Post-Fit values for their normalisations.'

l.360-361: 1) It is not clear from this statement what those pdfs are. 2) what are the correlations
  between different sources of uncertainty? In CMS the correlation between different uncertainty sources, a priori,
  is usually either -100%, 0%, or 100%.

between line 365 and 366: re-order the significance and best-fit signal strength values.

l.365-366: The claim of an excess of data events can be a bit misleading.
  Particularly when looking at mu_EW, I would say the background is a bit overestimated.
  It would be much better to start with
  'The best fit value for the signal
  strength mu_EW and its estimated uncertainty is
  mu_EW = 0.64 +0.45 - 0.37 (3).
  The significance of the signal is quantified by calculating the local p-value
  for an upward fluctuation of the data relative to the background prediction
  using a profile likelihood ratio test statistic
  and asymptotic formulae [56]. It is found to be ...
  [By the way: This has nothing to do with CLs (references).]

  Related comment: Equation (3): this is the fit result, is the uncertainty determined
  from the variation of -2ln L by +1 from the min. value.. where L
  is the profiled likelihood? --> better state that.
  Do you have more information on the best fit result, e.g. how much
  are nuisance pars shifted? You could
  also do a GOF-test, see https://twiki.cern.ch/twiki/bin/view/CMS/StatComGOF
  using the Baker-Cousins advocated likelihood chi2 test.

l.366: what you mean with stat. uncertainties, the ones of the data
  or also related to control regions or MC samples, etc.?

>>>>>>> Section 9 <<<<<<<<<
- it is not fully clear what is actually happening here.
  Is it correct that the aQGC parameters transform the EWK WZjj shape and norm?
  In that case the EWK WZjj contribution shown in Figure 4 is not strictly a background process;
  it is the null hypothesis and any other hypothesis (ie any of the couplings nonzero)
  does not contain exactly the EWK WZjj contribution as it is shown in Fig 4, is that correct?
  Howveer, if EW WZ is treated is background it should be included in the text that it contributes to the background.
  It only appears in the caption of figure 4.

- Previous limits could be shown for comparison.

l.390: There is not a single fit in the CLs criterion, but many. Would remove 'extracted from a maximum likelihood fit'
  and just leave 'extracted using the CLs criterion'. Additional comment: setting all parameters except for
  the coupling being probed to 0 is a valid assumption,
  but did you also try this leaving the unprobed parameters floating?

l.390: 'using the CLs criterion', please use this wording recommended by the Stat. Comm.
  Please take note that [59] = [54]

Fig. 4: 'shown as a filled histogram.' Aren't all backgrounds
  shown as filled histos?

Fig. 4: Perhaps it would be better to show this in log-y scale
 so one can see better the effect of the new physics at large m_T values.

Table 4: when you give 2-sided confidence intervals, I would prefer to call them confidence
intervals and not limits. Are you sure these are 95% C.L. and not 90% C.L.
intervals?

Fig. 5: how are the contour lines exactly defined?
Are you sure you take the 2d effect into account?
(e.g. a Delta_chi2 = +1 means 68% C.L. for 1D but only ~40% for 2D)

>>>>>>>>> Section 10 <<<<<<<<<
- Missing a figure with MT distribution containing signal distributions.
  Fig 4 does not count because the event selection for Higgs search is different.
- Previous limits could be shown for comparison.

l.410: 'CLs criterion' this is what the CMS Stat. Comm. suggests, method implies too much.

>>>>>>>>> Section 11 <<<<<<<<<
l.427: "extract the significance of EW WZ production" -> measure the signal strength of EW WZ production.
  Also quote the value actually measured here instead of only the significance


TYPE A
-------
l.5: 'to the Higgs' - should this still say 'Higgs boson'?

l.16: 'These interactions include WZ quartic couplings, as shown in Fig. 1 (a)'
  - this is repetitive as line 14 already state 'quartic WZ
  interactions are accessible through triple vector boson production or through vector boson scattering.
  Perhaps better to replace 'These interactions .. shown in Fig.1 (a)' with 'This is illustrated in Fig.1 (a)' or similar.

l.33: additional Higgs or other scalar bosons

l.73: spurious quotation mark at the end

l.191: 'single lepton trigger'

l.209 'negligible effect'

l.234: in a EW -> in  an EW

Figure 2: If using (a) and (b) subcaptions under the plots,
  then why not use these instead of (left) and (right) in the caption?
  Alternatively, drop the (a) and (b) subcaptions.

l.356: 'Extraction of the significance' -> 'Extraction of the signal strength'

l.383: 'formulation'

Table 4: CL limits for one -> CL intervals for each

Fig 4: caption: shouldn't this be standalone (ie not refer to the caption of another figure)?
 In general the captions of these figures are very long, is there any information that can be dropped?

Figure 5:
  - remove timestamp at the bottom left of the figure.
  - contour -> contours

Figure 6: The caption refers to (top) and (bottom) figures when the two plots are actualy side-by-side.

Figure 6: exclusion -> upper

<br/>%ENDTWISTY%

