## Current Status

Due to some essentially unfixable issues related to using the Comic Vine API (see [here](http://www.comicvine.com/forums/api-developers-2334/am-i-blocked-1714639/?page=1#js-message-15563948) and [here](https://github.com/cbanack/comic-vine-scraper/issues/421)), **I am no longer actively developing the Comic Vine Scraper project.**

The [latest release](https://github.com/cbanack/comic-vine-scraper/wiki/Download-and-Installation) of this app is functional as of Oct 17, 2015, and may well remain usable for quite some time.

The code here provides a solid example of how to properly use the [Comic Vine API](http://api.comicvine.com/), should you happen to want to create your own project that does that.   Also, if you are a relatively experienced python developer and you're interested in taking over Comic Vine Scraper, please feel free create your own fork and keep this project alive.

For those of you who've used and supported Comic Vine Scraper over the last 7 years, you have my sincere thanks for all your efforts and kind words.  It's been a blast!

-Cory

------------------------------------------------------------------------------------

## Docs and Binaries

All documentation about this project, including the latest downloads and installation instructions
can be found on the Comic Vine Scraper [Wiki page](https://github.com/cbanack/comic-vine-scraper/wiki/).

### Technical Details
 
This project is written for Windows, using IronPython and the .NET library.  It displays WinForms graphics and make heavy use of the [ComicVine RESTful API](http://www.comicvine.com/api/).  It is a _plugin_ for the [ComicRack](http://comicrack.cyolito.com/) comic book reader, which is a standalone Windows desktop application. Except during development (see below), Comic Vine Scraper does _not_ run outside of ComicRack's plugin environment.   

This project's repository is configured to compile and run in the [Eclipse IDE](https://eclipse.org/) using the [Aptana Pydev](http://pydev.org/) plugin with IronPython correctly installed and configured.

### Pull Requests

At this point, I am not accepting pull requests.  Comic Vine Scraper is a stable, mature project and most of the work on it these days is maintenance and bug fixing.  I may accept well-written pull requests for straightforward bug fixes, but _please contact me_ before you start doing any work.  I don't want to waste your time.

### License 

This project is created and distributed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).
This is an open source license, so you are welcome to create, build, and maintain your own fork of the codebase if you have a major enhancement that  you want to add, or a wild new direction that you'd like to take the project.

    Unless required by applicable law or agreed to in writing, software 
    distributed under this License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
