<ul>
<li>build - performs a one-time production build from the src/ directory + npm dependencies and outputs the resulting files into `public/`, invoked by running `npm run build`</li>
<li>start - starts a process on your computer that performs a one-time build and then watches your Plugin files for any changes and triggers a new build, invoked by running *pm start*</li>
<li>clean - removes all files from public/ except for any files in translations/, invoked by running *npm run clean*.  This is also run internally by the *npm run build* command, so it is only necessary for when you want to clean out the directory only</li>
<li>test - placeholder for you to put in the command to run your tests, invoked by running *npm test*</li>
</ul>