<template>
    <main>
        <div class="container">
            <img src="../assets/images/logo.svg" alt="" class="logo">
            <div class="wrapper">
                <h1 class="tagline">A history of everything you copy</h1>
                <p class="tag-description">Clipboard allows you to track and organize everything you
                    copy. Instantly access your clipboard on all your devices.</p>
            </div>
            <div class="cta-wrapper">
                <button class="cta cta1">Download for iOS</button>
                <button class="cta cta2">Download for Mac</button>
            </div>
            <div class="wrapper">
                <h1 class="feature-heading fh-1">Keep track of your snippets</h1>
                <p class="feature-description fd-1">Clipboard instantly stores any item you copy in the cloud,
                    meaning you can access your snippets immediately on all your
                    devices. Our Mac and iOS apps will help you organize everything.</p>
            </div>
            <div class="snippet-info">
                <div class="si-img">
                    <img src="../assets/images/image-computer.png" alt="" class="imac">
                </div>
                <div class="snippet-features">
                    <!-- 1 -->
                    <div class="sf-wrapper">
                        <h2 class="feature-heading fh-2">Quick Search</h2>
                        <p class="feature-description fd-2">Easily search your snippets by content, category, web address,
                            application, and
                            more.</p>
                    </div>

                    <!-- 2 -->
                    <div class="sf-wrapper">
                        <h2 class="feature-heading fh-2">iCloud Sync</h2>
                        <p class="feature-description fd-2">Instantly saves and syncs snippets across all your devices.</p>
                    </div>

                    <!-- 3 -->
                    <div class="sf-wrapper">
                        <h2 class="feature-heading fh-2">Complete History</h2>
                        <p class="feature-description fd-2">Retrieve any snippets from the first moment you started using
                            the
                            app.
                        </p>
                    </div>
                </div>
            </div>


            <h2 class="feature-heading fh-1">Access Clipboard anywhere</h2>
            <p class="feature-description fd-1">Whether you’re on the go, or at your computer, you can access all your
                Clipboard
                snippets in a few simple clicks.</p>

            <img src="../assets/images/image-devices.png" alt="" class="devices">

            <h2 class="feature-heading fh-1">Supercharge your workflow</h2>
            <p class="feature-description fd-1">We’ve got the tools to boost your productivity.</p>

            <div class="workflow-features">
                <!-- 1 -->
                <div class="wf-feature">
                    <img src="../assets/images/icon-blacklist.svg" alt="">
                    <h2 class="feature-heading">Create blacklists</h2>
                    <p class="feature-description">Ensure sensitive information never makes its way to your clipboard by
                        excluding
                        certain sources.</p>
                </div>

                <!-- 2 -->
                <div class="wf-feature">
                    <img src="../assets/images/icon-text.svg" alt="">
                    <h2 class="feature-heading">Plain text snippets</h2>
                    <p class="feature-description">Remove unwanted formatting from copied text for a consistent look.</p>
                </div>

                <!-- 3 -->
                <div class="wf-feature">
                    <img src="../assets/images/icon-preview.svg" alt="">
                    <h2 class="feature-heading">Sneak preview</h2>
                    <p class="feature-description">Quick preview of all snippets on your Clipboard for easy access.</p>
                </div>
            </div>

            <div class="partners">
                <img src="../assets/images/logo-google.png" alt="">
                <img src="../assets/images/logo-ibm.png" alt="">
                <img src="../assets/images/logo-microsoft.png" alt="">
                <img src="../assets/images/logo-hp.png" alt="">
                <img src="../assets/images/logo-vector-graphics.png" alt="">
            </div>

            <div class="wrapper">
                <h1 class="tagline">Clipboard for iOS and Mac OS</h1>
                <p class="tag-description">Available for free on the App Store. Download for Mac or iOS, sync with iCloud
                    and you’re ready to start adding to your clipboard.</p>
            </div>
            <div class="cta-wrapper">
                <button class="cta cta1">Download for iOS</button>
                <button class="cta cta2">Download for Mac</button>
            </div>

        </div>
        <div class="footer">
            <img src="../assets/images/logo.svg" alt="" class="footer-logo">
            <div class="backlinks">
                <div class="backlink-group">
                    <h4 class="backlink">FAQS</h4>
                    <h4 class="backlink">Contact Us</h4>
                </div>
                <div class="backlink-group">
                    <h4 class="backlink">Privacy Policy</h4>
                    <h4 class="backlink">Press Kit</h4>
                </div>
                <h4 class="backlink">Install Guide</h4>

            </div>

            <div class="social-icons">
                <img src="../assets/images/icon-facebook.svg" alt="">
                <img src="../assets/images/icon-twitter.svg" alt="">
                <img src="../assets/images/icon-instagram.svg" alt="">
            </div>
        </div>
    </main>
</template>
  
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bai+Jamjuree:wght@400;600&display=swap');

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

main {
    width: 100%;
    min-height: 100vh;
    background-color: white;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: start;
    background-image: url(../assets/images/bg-header-mobile.png);
    background-repeat: no-repeat;
    background-size: contain;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: start;
    width: 100%;
    padding: 0px 20px 0px 20px;
}

.logo {
    margin-top: 150px;
    margin-bottom: 100px;
}

.tagline {
    text-align: center;
    line-height: 1.1;
    font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 600;
    color: hsl(210, 10%, 33%);
    margin-bottom: 20px;
}

.tag-description {
    text-align: center;
    font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 400;
    color: hsl(201, 11%, 66%);
    margin-bottom: 40px;
}

.cta {
    width: 98%;
    height: 60px;
    background-color: hsl(171, 66%, 44%);
    border-radius: 40px;
    border: none;
    color: white;
    font-family: 'Bai Jamjuree', sans-serif;
    font-size: 16px;
    font-weight: 600;
}

.cta1 {
    margin-bottom: 20px;
    box-shadow: 0px 10px 10px hsla(171, 66%, 44%, 0.2);
}

.cta2 {
    background-color: hsl(233, 100%, 69%);
    box-shadow: 0px 10px 10px hsla(233, 100%, 69%, 0.2);
    margin-bottom: 150px;
}

.feature-heading {
    font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 600;
    color: hsl(210, 10%, 33%);
    text-align: center;
    margin-bottom: 5px;
}

.feature-description {
    font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 400;
    color: hsl(201, 11%, 66%);
    text-align: center;
}

.fh-1 {
    line-height: 1;
    font-size: 24px;
}

.fd-1 {
    margin-bottom: 30px;
}

.imac {
    width: 100%;
    margin-bottom: 40px;
}

.snippet-features {
    margin-bottom: 120px;
}

.sf-wrapper {
    margin-bottom: 30px;
}

.devices {
    width: 100%;
    margin-top: 30px;
    margin-bottom: 100px;
}

.workflow-features {
    margin-top: 40px;
    margin-bottom: 80px;
}

.wf-feature {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 50px;
}

.wf-feature img {
    margin-bottom: 20px;
}

.wf-feature h2 {
    margin-bottom: 20px;
}

.partners {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.partners img:last-child {
    margin-bottom: 150px;
}

.partners img {
    width: 120px;
    margin-bottom: 40px;
}

.footer {
    background-color: hsla(201, 11%, 66%, 0.2);
    width: 100%;
    padding: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.footer-logo {
    margin-top: 20px;
    margin-bottom: 50px;
    width: 50px;
}

.backlink {
    font-family: 'Bai Jamjuree', sans-serif;
    font-weight: 400;
    color: hsl(210, 10%, 33%);
    text-align: center;
    font-size: 18px;
    margin-bottom: 20px;
}

.social-icons {
    display: flex;
    margin-top: 30px;
    margin-bottom: 20px;
}

.social-icons img {
    margin-left: 20px;
    margin-right: 20px;
}

@media only screen and (min-width: 992px) {
    main {
        background-image: url(../assets/images/bg-header-desktop.png);
    }

    .wrapper {
        display: flex;
        flex-direction: column;
        width: 50%;
    }

    .tagline {
        font-size: 40px;
    }

    .tag-description {
        font-size: 18px;
    }

    .cta-wrapper {
        display: flex;
    }

    .cta {
        width: 200px;
        margin-left: 10px;
        margin-right: 10px;
    }

    .fh-1 {
        font-size: 35px;
        margin-bottom: 20px;
    }

    .fd-1 {
        font-size: 18px;
    }

    .snippet-info {
        height: 500px;
        width: 100%;
        display: flex;
        align-items: center;
    }

    .si-img {
        height: 100%;
        width: 50%;
        position: relative;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .imac {
        width: 80%;
        position: absolute;
        left: -40px;
        background-size: contain;
    }

    .snippet-features {
        width: 50%;
        height: 100%;
        margin-bottom: 0px;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .sf-wrapper {
        display: flex;
        flex-direction: column;
        align-items: start;
        width: 60%;
    }

    .sf-wrapper h2 {
        text-align: start;
    }

    .sf-wrapper p {
        text-align: start;
    }

    .devices {
        width: 60%;
    }

    .workflow-features {
        width: 94%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .wf-feature {
        width: 28%;
    }

    .partners {
        width: 90%;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 150px;
    }

    .partners img {
        margin-bottom: 0px;
    }

    .partners img:last-child {
        margin-bottom: 0px;
    }

    .footer {
        flex-direction: row;
        justify-content: space-between;
    }

    .backlinks {
        display: flex;
        flex-direction: row;
        align-items: start;
        width: 60%;
        height: 100px;
    }

    .backlink-group {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: space-between;
    }

    .backlink-group:first-child {
        margin-right: 80px;
    }

    .backlink-group:nth-child(2) {
        margin-right: 80px;
    }

    .backlink {
        margin-bottom: 0px;
    }

    .cta1 {
        transition: all 0.2s ease-in;
    }

    .cta2 {
        transition: all 0.2s ease-in;
    }

    .cta1:hover {
        background-color: hsla(171, 66%, 44%, 0.77);
        box-shadow: 0px 10px 10px hsla(171, 66%, 44%, 0.4);
    }

    .cta2:hover {
        background-color: hsla(233, 100%, 69%, 0.77);
        box-shadow: 0px 10px 10px hsla(233, 100%, 69%, 0.4);
    }
}
</style>
  