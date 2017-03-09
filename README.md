# Data Engineer Applicant Exercise

To be considered for a Data Engineer position at [Hedgeye](http://www2.hedgeye.com), you must successfully complete these steps [**](#footnote)

1. Fork this repository
2. In the *why_hire_me* directory
    * Add a file `cover_letter.txt` with cover letter type verbiage.
    * Fill out the `questionnaire.txt` and commit it
    * Add anything else we should know.  For example, one of your preferred development tools (editor, desktop app, etc.) and why you use it.
3. In the *simple_collection_process* directory, using the programming language / tool of your preference, create a script that collects 
the following information from the first 6 articles on our website [here](https://app.hedgeye.com/insights/all?type=insight) and saves it to a CSV file. 
    * Datetime Published
    * Headline
    * If an author exists (only first author):
      * Image Href
      * Name
      * Twitter Handle (leave blank if not present)
    * Content Body HTML
    * Include a copy of the CSV file generated from your run
    * Include run instructions (specify versions used)
    * Extra Credit: Download first image in content body and save to local filesystem
    * Tips
        * Write good code that you want people to see.
        * Make it easy to use
    * See [example article](https://app.hedgeye.com/insights/56827-investors-positioned-for-a-correction-are-positioned-for-failure) & illustrated data points:
    ![Sample Article](images/collect_data_points.jpg)
4. In the *simple_refactoring_exercise* directory you will find some several directories of code that needs to be refactored. Pick a language you are fluent in and refactor it. Let us know in your cover letter which language you chose.
    * Tests/specs are included.
    * Please [refactor](http://www.refactoring.com) the implementation. Clarity and duplication are a given, flawed implementation is also likely.
    * Please note: feel free to change the tests/specs, but they should all be passing when you turn in your code.
    * Leave a note about what you refactored and why.  Calling specific named smells and specific named refactorings should be the norm.    
5. Commit and Push your code to your fork
6. Send a pull request, we will review your code and get back to you. If your GitHub profile does not include your name, please include your name in the pull request.



<a name="footnote"></a>** The awesome idea of github pull request as
job application task was previously done by [Integrum](http://integrumtech.com) [here](https://github.com/integrum/job-application)
