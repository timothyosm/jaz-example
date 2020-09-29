<template>
  <div id="container">
    <el-row id="caro">
      <el-carousel :interval="10000" arrow="always">
        <el-carousel-item>
          <el-row style="background-color: #0099ff">
            <el-col :span="6"
              ><div class="grid-content bg-purple"></div
            ></el-col>
            <el-col :span="6">
              <div style="margin-top: 50px; margin-left: 50px">
                <h1 class="title">Branding</h1>
                <p>Are you looking to:</p>
                <ul>
                  <li>Create a new brand</li>
                  <li>Re-develop or invigorate an existing brand</li>
                  <li>Build brand awareness</li>
                </ul>
                <p>
                  Or not sure but want some advice and direction on branding?
                </p>
                <el-button>Let's Talk</el-button>
              </div>
            </el-col>
            <el-col :span="6">
              <img src="..\assets\Jaz-Branding-Iron_v2.png" alt="" />
            </el-col>
            <el-col :span="6"
              ><div class="grid-content bg-purple-light"></div
            ></el-col>
          </el-row>
        </el-carousel-item>

        <el-carousel-item>
          <el-row style="background-color: #9164cc">
            <el-col :span="6"
              ><div class="grid-content bg-purple"></div
            ></el-col>
            <el-col :span="6">
              <div style="margin-top: 50px; margin-left: 50px">
                <h1 class="title">Design</h1>
                <p>
                  Are you looking for that creative edge to stand out from all
                  the others and create that everlasting impression? Perhaps
                  some marketing collateral?
                </p>
                <p>Or do you just need a bit of Jazzing up?</p>
                <el-button>Let's Talk</el-button>
              </div>
            </el-col>
            <el-col :span="6">
              <img src="..\assets\Design2.png" alt="" />
            </el-col>
            <el-col :span="6"
              ><div class="grid-content bg-purple-light"></div
            ></el-col>
          </el-row>
        </el-carousel-item>

        <el-carousel-item>
          <el-row style="background-color: #ff6c0e">
            <el-col :span="6"
              ><div class="grid-content bg-purple"></div
            ></el-col>
            <el-col :span="6">
              <img src="..\assets\ladder-angle-1.png" alt="" />
            </el-col>
            <el-col :span="6">
              <div style="margin-top: 50px; margin-left: 50px">
                <h1 class="title">Marketing</h1>
                <p>
                  Is your marketing cutting the mustard and getting the results
                  you want? Do you know you need to be marketing but not sure
                  where to start?
                </p>
                <p>
                  Or maybe are you looking for a fresh approach and new &
                  creative ideas?
                </p>
                <el-button>Let's Talk</el-button>
              </div>
            </el-col>
            <el-col :span="6"
              ><div class="grid-content bg-purple-light"></div
            ></el-col>
          </el-row>
        </el-carousel-item>
      </el-carousel>
    </el-row>


    <el-row :gutter="20" style="position:relative; bottom:180px">
    <h1 style="text-align: center">Here's what people are saying about Jaz Creative</h1>

      <el-col :span="6">
        <el-card style="width: 20rem; text-align: center">
          <div slot="header" class="clearfix">
            <blockquote>
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud."
            </blockquote>
          </div>
          <div>Sarah Kline</div>
          <div>Company</div>
          <el-avatar
            size="50"
            src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"
          ></el-avatar>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card style="width: 20rem; text-align: center">
          <div slot="header" class="clearfix">
            <blockquote>
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud."
            </blockquote>
          </div>
          <div>Sarah Kline</div>
          <div>Company</div>
          <el-avatar
            size="50"
            src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"
          ></el-avatar>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card style="width: 20rem; text-align: center">
          <div slot="header" class="clearfix">
            <blockquote>
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud."
            </blockquote>
          </div>
          <div>Sarah Kline</div>
          <div>Company</div>
          <el-avatar
            size="50"
            src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"
          ></el-avatar>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card style="width: 20rem; text-align: center">
          <div slot="header" class="clearfix">
            <blockquote>
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud."
            </blockquote>
          </div>
          <div>Sarah Kline</div>
          <div>Company</div>
          <el-avatar
            size="50"
            src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"
          ></el-avatar>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style>
.el-row {
  margin-bottom: 0px !important;
  height: 50rem !important;
}
#caro {
  color: white;
}
.title {
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
  text-size-adjust: 100%;
  font-family: BlinkMacSystemFont, -apple-system, "Segoe UI", "Roboto", "Oxygen",
    "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue",
    "Helvetica", "Arial", sans-serif;
  --columnGap: 2rem;
  box-sizing: inherit;
  margin: 0;
  padding: 0;
  word-break: break-word;
  line-height: 1.125;
  font-weight: 700 !important;
  margin-bottom: 1.2rem !important;
  font-size: 2rem;
  color: fff;
}

.el-carousel__container {
  height: 37.4rem !important;
}

.el-row {
  margin-bottom: 20px;
  &:last-child {
    margin-bottom: 0;
  }
}
.el-col {
  border-radius: 4px;
}
.bg-purple-dark {
  /* background: #99a9bf; */
}
.bg-purple {
  /* background: #d3dce6; */
}
.bg-purple-light {
  /* background: #e5e9f2; */
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.row-bg {
  padding: 10px 0;
  /* background-color: #f9fafc; */
}
</style>