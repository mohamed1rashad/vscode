   المساهمة في VS Code 

مساهماتك في المصادر المفتوحة، الكبيرة أو الصغيرة، تجعل مثل هذه المشاريع الكبيرة ممكنة. شكرا لأخذ الوقت للمساهمة.

هناك عدة طرق يمكنك من خلالها المساهمة، بخلاف كتابة التعليمات البرمجية. الهدف من هذه الوثيقة هو تقديم نظرة عامة رفيعة المستوى حول كيفية المشاركة. المساهمة في VS Code

##    طرح الأسئلة؟  


 هل لديك سؤال؟ بدلاً من فتح مشكلة، يرجى السؤال.   [كومة تجاوز.](https://stackoverflow.com/questions/tagged/visual-studio-code)    باستخدام العلامة. 'visual-studio-code`.  

سيكون المجتمع النشط حريصًا على مساعدتك. سيكون سؤالك المتقن الصياغة بمثابة مورد للآخرين الذين يبحثون عن المساعدة.

##   تقديم التغذية الراجعة. 

تعليقاتك وتعليقاتك مرحب بها، وفريق التطوير متاح عبر حفنة من القنوات المختلفة.

 انظر...   [قنوات التغذية الراجعة.](https://github.com/microsoft/vscode/wiki/Feedback-Channels)   صفحة ويكي للحصول على تفاصيل حول كيفية مشاركة أفكارك. 

##  الإبلاغ عن القضايا.

هل حددت مشكلة قابلة للتكرار في VS Code؟ هل لديك طلب ميزة؟ نريد أن نسمع عن ذلك! إليك كيف يمكنك الإبلاغ عن مشكلتك بأكبر قدر ممكن من الفعالية.

###  تحديد مكان الإبلاغ

يتم توزيع مشروع رمز VS عبر مستودعات متعددة. حاول تقديم المشكلة ضد المستودع الصحيح. تحقق من قائمة...  [المشاريع ذات الصلة.](https://github.com/microsoft/vscode/wiki/Related-Projects)  إذا لم تكن متأكدًا من الريبو الصحيح.

هل حددت مشكلة قابلة للتكرار في VS Code؟ هل لديك طلب ميزة؟ نريد أن نسمع عن ذلك! إليك كيف يمكنك الإبلاغ عن مشكلتك بأكبر قدر ممكن من الفعالية.

### ابحث عن مشكلة قائمة

قبل إنشاء مشكلة جديدة، يرجى إجراء بحث في... [القضايا المفتوحة.](https://github.com/microsoft/vscode/issues) لمعرفة ما إذا كان قد تم بالفعل تقديم طلب المشكلة أو الميزة.

هناك عدة طرق يمكنك من خلالها المساهمة، بخلاف كتابة التعليمات البرمجية. الهدف من هذه الوثيقة هو تقديم نظرة عامة رفيعة المستوى حول كيفية المشاركة.مرحبًا بك، وشكراً لاهتمامك بالمساهمة في VS Code!#](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc) feature requests.

إذا وجدت مشكلتك موجودة بالفعل، فقم بإجراء تعليقات ذات صلة وأضف مشكلتك. [رد الفعل.](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments). استخدم رد فعل بدلاً من تعليق "+1":

  صفحة ويكي للحصول على تفاصيل حول كيفية مشاركة أفكارك.مرحبًا بك، وشكراً لاهتمامك بالمساهمة في VS Code!
* 👎 - downvote

If you cannot find an existing issue that describes your bug or feature, create a new issue using the guidelines below.

### Writing Good Bug Reports and Feature Requests

File a single issue per problem and feature request. Do not enumerate multiple bugs or feature requests in the same issue.

Do not add your issue as a comment to an existing issue unless it's for the identical input. Many issues look similar but have different causes.

The more information you can provide, the more likely someone will be successful at reproducing the issue and finding a fix.

The built-in tool for reporting an issue, which you can access by using `Report Issue` in VS Code's Help menu, can help streamline this process by automatically providing the version of VS Code, all your installed extensions, and your system info. Additionally, the tool will search among existing issues to see if a similar issue already exists.

Please include the following with each issue:

* Version of VS Code
* Your operating system
* List of extensions that you have installed
* Reproducible steps (1... 2... 3...) that cause the issue
* What you expected to see, versus what you actually saw
* Images, animations, or a link to a video showing the issue occurring
* A code snippet that demonstrates the issue or a link to a code repository the developers can easily pull down to recreate the issue locally
  * **Note:** Because the developers need to copy and paste the code snippet, including a code snippet as a media file (i.e. .gif) is not sufficient.
* Errors from the Dev Tools Console (open from the menu: Help > Toggle Developer Tools)

### Creating Pull Requests

* Please refer to the article on [creating pull requests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests) and contributing to this project.

### Final Checklist

Please remember to do the following:

* [ ] ابحث في مستودع المشكلات للتأكد من أن تقريرك يمثل مشكلة جديدة.
* [ ] Recreate the issue after disabling all extensions
* [ ] Simplify your code around the issue to better isolate the problem

Don't feel bad if the developers can't reproduce the issue right away. They will simply ask for more information!

### Follow Your Issue

Once submitted, your report will go into the [issue tracking](https://github.com/microsoft/vscode/wiki/Issue-Tracking) workflow. Be sure to understand what will happen next, so you know what to expect and how to continue to assist throughout the process.

## Automated Issue Management

We use GitHub Actions to help us manage issues. These Actions and their descriptions can be [viewed here](https://github.com/microsoft/vscode-github-triage-actions). Some examples of what these Actions do are:

* Automatically close any issue marked `info-needed` if there has been no response in the past 7 days.
* Automatically lock issues 45 days after they are closed.
* Automatically implement the VS Code [feature request pipeline](https://github.com/microsoft/vscode/wiki/Issues-Triaging#managing-feature-requests).

If you believe the bot got something wrong, please open a new issue and let us know.

## Contributing Fixes

If you are interested in writing code to fix issues, please see [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute) in the wiki.

## Thank You

Your contributions to open source, large or small, make great projects like this possible. Thank you for taking the time to contribute.
