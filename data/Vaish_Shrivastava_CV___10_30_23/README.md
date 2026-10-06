# CV source

Edit `main.tex`, then run `make` from this directory to rebuild both versions:
`../Vaishnavi_Shrivastava_CV.pdf`, the numbered version linked from the website,
and `../Vaishnavi_Shrivastava_CV_unnumbered.pdf`, the version without publication
numbers. Both share the same content in `main.tex`; `unnumbered.tex` selects
the alternate layout. Run `make unnumbered` to build only that version.
The build requires pdfLaTeX with `enumitem`, `ulem`, `microtype`, `xcolor`, and `hyperref`
(available in TeX Live and Overleaf). Temporary output goes in `build/`.
In Overleaf, select `main.tex` or `unnumbered.tex` as the main document and
pdfLaTeX as the compiler.

The layout follows [Shashank Gupta's CV](https://shashankgupta.info/data/ShashankGupta-CV.pdf):
Computer Modern type, a left column of small-cap section labels, a name and rule
at the top, experience before publications, italic
dates, and publications with underlined titles. Publications are grouped into
Peer-Reviewed Publications and Preprints & Technical Reports in the owner's
chosen order. The numbered version counts down separately within each section
(7--1 and 5--1); the alternate version omits the numbers.

Contact details occupy one line in the main text column beside a Contact label,
with centered-dot separators. All four links
use black text with light gray solid underlines.

Employment follows [Unnat Jain's CV](https://unnat.github.io/resume.pdf): one
combined section with bold sans-serif organization names, regular-weight locations and roles,
and dates aligned right without brackets. Advisor details appear below the role;
research themes use small italic text separated by centered dots without a label.
Older software engineering internships are combined on one line.
The current role's title, Senior Researcher, is also set in bold sans-serif to
give it subtle emphasis while keeping the location and dates at regular weight.

The retained sections are Contact, Education, Employment, Peer-Reviewed
Publications, Preprints & Technical Reports, Teaching Experience, and References.
Research Interests, Selected Research Projects, Technical Skills, Talks, and
Selected Leadership Positions have been removed.

Both degrees list a GPA of 3.9/4.0, and Stanford's education dates are 2022--2024,
as supplied by the owner. The owner confirmed that the Stanford RA role ended
in June 2024 and the Senior Researcher role at Microsoft Research in Redmond,
WA began in September 2024 and is current.

The publication list was checked against the owner's
[Google Scholar profile](https://scholar.google.com/citations?hl=en&user=N0nX2VsAAAAJ&view_op=list_works&sortby=pubdate&pagesize=100)
on September 28, 2026. Seven papers from 2025--2026 were added to the existing
five. The profile's older 2015 acoustics abstract was outside this update of
newer papers; its patent record is reflected in the existing UserIdentifier entry.
Titles and full author lists were checked against these primary sources:

| Added paper | Sources and venue |
| --- | --- |
| SuperThoughts: Reasoning Tokens in Superposition | [arXiv, 2026](https://arxiv.org/abs/2606.13862) |
| ECHO: Terminal Agents Learn World Models for Free | [arXiv](https://arxiv.org/abs/2605.24517); NeurIPS 2026 Spotlight acceptance confirmed by the owner; [OpenReview](https://openreview.net/forum?id=9rkAbf5ICO) may not yet be public |
| Wait, Wait, Wait... Why Do Reasoning Models Loop? | [ICML 2026 Spotlight, OpenReview](https://openreview.net/forum?id=oZWE7mSqlk); [arXiv](https://arxiv.org/abs/2512.12895) |
| Sample More to Think Less: Group Filtered Policy Optimization for Concise Reasoning | [arXiv](https://arxiv.org/abs/2508.09726); [official ICLR 2026 proceedings](https://proceedings.iclr.cc/paper_files/paper/2026/hash/a00ef870c140f09263ba2288855be50b-Abstract-Conference.html) |
| Not All Thoughts Matter: Selective Attention for Efficient Reasoning | [paper PDF](https://openreview.net/pdf?id=BYmprj67tk); [author's OpenReview record, NeurIPS 2025 ER Workshop](https://openreview.net/profile?id=~Guoqing_Zheng1) |
| Phi-4-reasoning Technical Report | [arXiv, 2025](https://arxiv.org/abs/2504.21318); authors listed alphabetically by last name |
| Language Models Prefer What They Know: Relative Confidence Estimation via Confidence Preferences | [arXiv, 2025](https://arxiv.org/abs/2502.01126) |

For Sample More to Think Less, the official ICLR proceedings establish the
conference year as 2026, correcting the profile's 2025 venue label. The blank
year on the workshop paper's Scholar record is filled as 2025 from OpenReview.
Author-line years retain the initial release year, while venue lines give the
conference year where applicable.

Conference paper titles link to the official proceedings or OpenReview entry
when publicly available; preprints link to arXiv. At the owner's request, ECHO
retains its arXiv link until its NeurIPS page is public, while its venue line
records the NeurIPS 2026 Spotlight acceptance. The three ICLR papers use the ICLR proceedings pages
([Sample More to Think Less](https://proceedings.iclr.cc/paper_files/paper/2026/hash/a00ef870c140f09263ba2288855be50b-Abstract-Conference.html),
[Generator-Validator Consistency](https://proceedings.iclr.cc/paper_files/paper/2024/hash/bfcb583d225b1db8d3ca2331f6785774-Abstract-Conference.html),
and [Bias Runs Deep](https://proceedings.iclr.cc/paper_files/paper/2024/hash/5e1a87dbb7e954b8d9d6c91f6db771eb-Abstract-Conference.html)).
UserIdentifier links to [ACL Anthology](https://aclanthology.org/2022.naacl-main.252/).
The MSJar article retains its arXiv link because a public journal landing page
was not found.

Llamas Know What GPTs Don't Show is labeled as an
[arXiv preprint](https://arxiv.org/abs/2311.08877), replacing its old review status.
The UserIdentifier patent note reflects the December 31, 2024 grant of
[U.S. Patent 12,182,511](https://patents.google.com/patent/US12182511B2/en).
