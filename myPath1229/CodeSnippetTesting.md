# Code Snippet Testing



<!-- BEGINSECTION class="tabbedCodeSnippets" -->
```cs-i
public void APILandingPage_AutoFilterWithMoreThanThreeAndZero()
        {
            //would change this after the page is migrated over to en-us
            APIFilter filter = FindControlOnPage<APIFilter>();

            // with 2 characters, 
            filter.FilterBoxText = "AP";
            List<APIFilterResult> result = filter.FilterResultSet;
            Assert.IsTrue(result.Count == 0, "There should be not result match");

            filter.FilterBoxText = "API";
            result = filter.FilterResultSet;
            Assert.IsTrue(result.Count > 0, "There should be at least one match.");
        }

test the scroll bar
Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")Assert.IsTrue(result.Count > 0, "There should be at least one match.")
 ```
 
 ```javascript-i
var inches = 12;
 ```
<!-- ENDSECTION --> 

