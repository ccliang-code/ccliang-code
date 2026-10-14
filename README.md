# Hi, I'm Chia-Chen

I take things that experts judge by eye and turn them into numbers that hold up.

So far that has meant tumors in mammograms, pain in mice, which trauma patients are about to need a
chest tube, and which pixel in a satellite image is a rooftop and which is a parking lot. Different
fields, same job.

Ph.D. in Electrical Engineering. Now a postdoctoral fellow at the University of Maryland,
Baltimore, where I build machine learning models on clinical data and then spend most of my time
trying to break them.

### Code up here

**[IRTS-CNN](https://github.com/ccliang-code/IRTS-CNN)** — hyperspectral image classification with
iterative random training sampling. Python.
[IEEE TGRS 61, 2023](https://doi.org/10.1109/TGRS.2023.3280205)

**[HOCD](https://github.com/ccliang-code/HOCD)** — my favorite result, and the most humbling one.
The deep networks I had built scored 98.59% on the standard benchmark. Then I stopped telling them
what every object in the scene was, which is the only honest setup, because nobody can list every
material in a real image in advance. They scored **2.56%**. A closed-set classifier has no way to
say "none of these", so it confidently assigns every unknown pixel to whichever class it resembles
most. HOCD asks "is this anything I know?" before asking "which one?", and held 91%. MATLAB.
[IEEE TGRS 63, 2025](https://doi.org/10.1109/TGRS.2024.3511953)

### Other things that are true

Corresponding author on three IEEE TGRS papers, and now an invited reviewer for the same journal,
which mostly means I get to be the person asking other people where their numbers came from.



<!--
**ccliang-code/ccliang-code** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
