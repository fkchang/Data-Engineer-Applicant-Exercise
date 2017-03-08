# Data Engineer Applicant Exercise

To be considered for a developer position at [Hedgeye](http://www2.hedgeye.com), you must successfully complete these steps [**](#footnote)

**Please note:** your code will be tested on Ruby 1.9.3 and the latest version of Chrome.

1. Fork this repository
1. In the *why_hire_me* directory
    * Add a file `cover_letter.txt` with cover letter type verbiage.
    * Fill out the `questionnaire.txt` and commit it
    * Anything else we should know.  For example, one of your preferred development tools (editor, desktop app, etc.) and why you use it.
1. In the *simple_collection_process* directory, using the programming language / tool of your preference, create a script that collects 
the following information from the first 6 articles on our website [here](https://app.hedgeye.com/insights/all?type=insight) and saves it to a CSV file. 
    * Datetime Published
    * Headline
    * If an author exists (only first author):
      * Image Href
      * Name
      * Twitter Handle (leave blank if not present)
    * Content Body HTML
    * Include a copy of the CSV file generated from your run
    * Extra Credit: Download first image in content body and save to local filesystem
    * Tips
        * Write good code that you want people to see.
        * Make it easy to use so we can run it and see the results
    * See [example article](https://app.hedgeye.com/insights/56827-investors-positioned-for-a-correction-are-positioned-for-failure) & illustrated data points:
    ![Sample Article](images/collect_data_points.jpg)
6. Commit and Push your code to your fork
7. Send a pull request, we will review your code and get back to you.  If your GitHub profile does not include your name, please include your name in the pull request.



<a name="footnote"></a>** The awesome idea of github pull request as
job application task was previously done by [Integrum](http://integrumtech.com) [here](https://github.com/integrum/job-application)
