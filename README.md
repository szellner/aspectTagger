# aspect-tagger
A short script to tag square and panoramic images.
### Synopsis
A bash script that tags square and panoramic images. Easily find Instagram photos, profile pictures, color/bump/normal/etc. maps, tiling textures, panoramic vacation photos and more. Once images are tagged, set even more specific tags like ‘instagram’ or ‘specular maps’ to make searching a breeze!

### Code Example
Run for home directory (the default root): 
./aspectTagger.sh 

Run for a specific folder: 
./aspectTagger.sh ~/SomeFolder

Note: tag.sh can be run by itself, but is meant more as a helper file. 

### Motivation
Finder can filter by portrait or landscape orientation, but panoramic and square photos are more specific (and useful) targets. After searching for solutions, the best I could find was <a href="https://discussions.apple.com/thread/3838377?start=0&amp;amp;tstart=0">this</a>. However, the script provided doesn’t work for me for a few reasons:
<ul>
<li>It changes the filenames rather than just tagging the images
<li>I wanted to exclude the system files contained in my Library folder
<li>There’s no way to exclude icons and small UI elements
<li>I wanted to use multiprocessing to make tagging faster
</ul>

### Installation
<ol>
<li>Download or clone aspectTagger.
<li>Open Terminal (located at ~/Applications/Utilities/Terminal.app)
<li>In Terminal, navigate to where you’ve downloaded the scripts
<li>Install <a href="https://github.com/jdberry/tag">tag</a> using your preferred method
</ol>
