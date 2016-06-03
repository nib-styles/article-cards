# @nib-styles/article-cards

Fixed width news article cards for nib pages. Used for the homepage and /nib-news

## Installation

    npm install --save @nib-styles/article-cards

## Usage

Card grid can be limited to 3 columns or unlimited and fill the space.

    <div class="article-cards article-cards--limited-to-three-columns">
        
        <a class="article-card"></a>
        <a class="article-card"></a>
        <a class="article-card"></a>
        
     </div>

There are three categories of `article-card`:
- Media
- Health Cover
- Healthy Life

      <a class="article-card article-card--media"></a>
      <a class="article-card article-card--health-cover"></a>
      <a class="article-card article-card--health-life"></a>
       

An article-card is comprised of a date, title, blurb and link:


    <div class="article-cards article-cards--limited-to-three-columns">
        <a class="article-card article-card--media" href="#">
            <p class="article-card__date">02 June 2016</p>
            <h1 class="article-card__title">Netus blandit habitant cursus</h1>
            <p class="article-card__blurb">
                Diam adipiscing orci ullamcorper feugiat dapibus a lacus sagittis a nulla feugiat a phasellus netus blandit habitant cursus scelerisque quisque taciti enim.
            </p>
            <div class="article-card__link">Read full article</div>
        </a>
    </div>

Articles can omit any of these elements (e.g. blurb). A group of articles should contain the same elements to maintain equal heights.