<template>
  <div class="card-inner" id="works-card">
    <div class="card-wrap" style="">
      <div class="content works">
        <!-- title -->
        <div class="title"><span class="first-word">Recent</span> Works</div>

        <!-- filters -->
        <div class="filter-menu filter-button-group">
          <div class="f_btn active">
            <label>
              <input type="radio" name="fl_radio" value="grid-item" />All</label
            >
          </div>
          <div class="f_btn">
            <label>
              <input type="radio" name="fl_radio" value="photo" />Image
            </label>
          </div>
          <div class="f_btn">
            <label>
              <input type="radio" name="fl_radio" value="gallery" />Gallery
            </label>
          </div>
          <div class="f_btn">
            <label>
              <input type="radio" name="fl_radio" value="video" />Video
            </label>
          </div>
          <div class="f_btn">
            <label>
              <input type="radio" name="fl_radio" value="music" />Music
            </label>
          </div>
          <div class="f_btn">
            <label>
              <input type="radio" name="fl_radio" value="design" />Content
            </label>
          </div>
        </div>

        <!-- content -->
        <div
          class="row grid-items border-line-v"
          style="position: relative; height: 1309.16px"
        >
          <!-- work item photo -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item photo border-line-h"
            style="position: absolute; left: 0%; top: 0px"
          >
            <div class="box-item">
              <div class="image">
                <a
                  :href="require('@/assets/images/works/work1.jpg')"
                  class="has-popup-image"
                >
                  <img src="@/assets/images/works/work1.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-image" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a
                  :href="require('@/assets/images/works/work1.jpg')"
                  class="name has-popup-image"
                >
                  Motorcycle Helmet
                </a>
                <div class="category">Image</div>
              </div>
            </div>
          </div>

          <!-- work item video -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item video border-line-h"
            style="position: absolute; left: 49.9973%; top: 0px"
          >
            <div class="box-item">
              <div class="image">
                <a href="https://vimeo.com/97102654" class="has-popup-video">
                  <img src="@/assets/images/works/work2.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-videocamera" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a
                  href="https://vimeo.com/97102654"
                  class="name has-popup-video"
                  >Minimalism Shapes</a
                >
                <div class="category">Video</div>
              </div>
            </div>
          </div>

          <!-- work item music -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item music border-line-h"
            style="position: absolute; left: 49.9973%; top: 251.984px"
          >
            <div class="box-item">
              <div class="image">
                <a
                  href="https://w.soundcloud.com/player/?visual=true&amp;url=http%3A%2F%2Fapi.soundcloud.com%2Ftracks%2F221650664&amp;show_artwork=true"
                  class="has-popup-music"
                >
                  <img src="@/assets/images/works/work3.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-music-note" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a href="#" class="name has-popup">Staircase</a>
                <div class="category">Music</div>
              </div>
            </div>
          </div>

          <!-- work item design -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item design border-line-h"
            style="position: absolute; left: 0%; top: 406.969px"
          >
            <div class="box-item">
              <div class="image">
                <a href="#popup-1" class="has-popup-media">
                  <img src="@/assets/images/works/work4.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-images" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a href="#popup-1" class="name has-popup-media"
                  >Mobile Application</a
                >
                <div class="category">Content</div>
              </div>
              <div id="popup-1" class="popup-box mfp-fade mfp-hide">
                <div class="content">
                  <div class="image">
                    <img src="@/assets/images/works/work4.jpg" alt="" />
                  </div>
                  <div class="desc">
                    <div class="post-box">
                      <h1>Mobile Application</h1>
                      <div class="blog-detail">Design</div>
                      <div class="blog-content">
                        <p>
                          So striking at of to welcomed resolved. Northward by
                          described up household therefore attention. Excellence
                          decisively nay man yet impression for contrasted
                          remarkably.
                        </p>
                        <p>
                          Forfeited you engrossed but gay sometimes explained.
                          Another as studied it to evident. Merry sense given he
                          be arise. Conduct at an replied removal an amongst.
                          Remaining determine few her two cordially admitting
                          old.
                        </p>
                        <blockquote>
                          Vestibulum ante ipsum primis in faucibus orci luctus
                          et ultrices posuere cubilia Curae; Pellentesque
                          suscipit.
                        </blockquote>
                        <p>
                          Tiled say decay spoil now walls meant house. My mr
                          interest thoughts screened of outweigh removing.
                          Evening society musical besides inhabit ye my. Lose
                          hill well up will he over on. Increasing sufficient
                          everything men him admiration unpleasing sex.
                        </p>
                        <ul class="list-style">
                          <li>Greatest properly off ham exercise all.</li>
                          <li>Unsatiable invitation its possession nor off.</li>
                          <li>
                            All difficulty estimating unreserved increasing the
                            solicitude.
                          </li>
                        </ul>
                        <p>
                          Unpleasant astonished an diminution up partiality.
                          Noisy an their of meant. Death means up civil do an
                          offer wound of.
                        </p>
                      </div>
                      <a href="#" class="button">
                        <span class="text">View Project</span>
                        <span class="arrow" />
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- work item photo -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item gallery border-line-h"
            style="position: absolute; left: 49.9973%; top: 503.968px"
          >
            <div class="box-item">
              <div class="image">
                <a href="#gallery-1" class="has-popup-gallery">
                  <img src="@/assets/images/works/work5.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-images" />
                  </span>
                </a>
                <div id="gallery-1" class="mfp-hide">
                  <a :href="require('@/assets/images/works/work6.jpg')"></a>
                  <a :href="require('@/assets/images/works/work1.jpg')"></a>
                  <a :href="require('@/assets/images/works/work5.jpg')"></a>
                </div>
              </div>
              <div class="desc">
                <a
                  :href="require('@/assets/images/works/work5.jpg')"
                  class="name has-popup-image"
                >
                  Gereal Travels
                </a>
                <div class="category">Gallery</div>
              </div>
            </div>
          </div>

          <!-- work item music -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item music border-line-h"
            style="position: absolute; left: 0%; top: 697.703px"
          >
            <div class="box-item">
              <div class="image">
                <a
                  href="https://w.soundcloud.com/player/?visual=true&amp;url=http%3A%2F%2Fapi.soundcloud.com%2Ftracks%2F221650664&amp;show_artwork=true"
                  class="has-popup-music"
                >
                  <img src="@/assets/images/works/work8.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-music-note" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a href="#" class="name has-popup">Daylight Entrance</a>
                <div class="category">Music</div>
              </div>
            </div>
          </div>

          <!-- work item video -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item video border-line-h"
            style="position: absolute; left: 49.9973%; top: 902.187px"
          >
            <div class="box-item">
              <div class="image">
                <a href="https://vimeo.com/97102654" class="has-popup-video">
                  <img src="@/assets/images/works/work6.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-videocamera" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a
                  href="https://vimeo.com/97102654"
                  class="name has-popup-video"
                  >Architecture</a
                >
                <div class="category">Video</div>
              </div>
            </div>
          </div>

          <!-- work item design -->
          <div
            class="col col-d-6 col-t-6 col-m-12 grid-item design border-line-h"
            style="position: absolute; left: 0%; top: 969.062px"
          >
            <div class="box-item">
              <div class="image">
                <a href="#popup-2" class="has-popup-media">
                  <img src="@/assets/images/works/work7.jpg" alt="" />
                  <span class="info">
                    <span class="ion ion-images" />
                  </span>
                </a>
              </div>
              <div class="desc">
                <a href="#popup-2" class="name has-popup-media"
                  >Social Website</a
                >
                <div class="category">Content</div>
              </div>
              <div id="popup-2" class="popup-box mfp-fade mfp-hide">
                <div class="content">
                  <div class="image">
                    <img src="@/assets/images/works/work7.jpg" alt="" />
                  </div>
                  <div class="desc">
                    <div class="post-box">
                      <h1>Mobile Application</h1>
                      <div class="blog-detail">Design</div>
                      <div class="blog-content">
                        <p>
                          So striking at of to welcomed resolved. Northward by
                          described up household therefore attention. Excellence
                          decisively nay man yet impression for contrasted
                          remarkably.
                        </p>
                        <p>
                          Forfeited you engrossed but gay sometimes explained.
                          Another as studied it to evident. Merry sense given he
                          be arise. Conduct at an replied removal an amongst.
                          Remaining determine few her two cordially admitting
                          old.
                        </p>
                        <blockquote>
                          Vestibulum ante ipsum primis in faucibus orci luctus
                          et ultrices posuere cubilia Curae; Pellentesque
                          suscipit.
                        </blockquote>
                        <p>
                          Tiled say decay spoil now walls meant house. My mr
                          interest thoughts screened of outweigh removing.
                          Evening society musical besides inhabit ye my. Lose
                          hill well up will he over on. Increasing sufficient
                          everything men him admiration unpleasing sex.
                        </p>
                        <ul class="list-style">
                          <li>Greatest properly off ham exercise all.</li>
                          <li>Unsatiable invitation its possession nor off.</li>
                          <li>
                            All difficulty estimating unreserved increasing the
                            solicitude.
                          </li>
                        </ul>
                        <p>
                          Unpleasant astonished an diminution up partiality.
                          Noisy an their of meant. Death means up civil do an
                          offer wound of.
                        </p>
                      </div>
                      <a href="#" class="button">
                        <span class="text">View Project</span>
                        <span class="arrow" />
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="clear"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Works",
  components: {},
};
</script>
