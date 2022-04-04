<template>
    <header class="header">
        <div class="container">
            <div class="header__box">
                <a
                  href="/"
                  aria-label="Go to Home"
                  title="Go to Home"
                >
                    <img class="me-5" src="src/assets/img/logo.png" alt="Logo Youtube" height="auto" width="150">
                </a>

                <div class="d-none d-md-block ms-lg-5 ps-lg-5 flex-fill">
                    <div class="header__item">
                        <div class="search">
                            <input
                                type="text"
                                name="search"
                                aria-label="Search"
                                placeholder="Search"
                            />

                            <button
                                class="search__button"
                                type="button"
                                aria-label="Search"
                            >
                                Search
                            </button>
                        </div>
                
                        <p><b><a href="#" aria-label="Go to Create account" title="Go to Create account">Create Account</a> or <a href="#" aria-label="Go to Sign-in" title="Go to Sign-in">Sign-in</a></b></p>
                    </div>

                    <div class="header__item">
                        <nav class="headerNav">
                            <a href="#" class="headerNav__item" aria-label="Go to Home" title="Go to Home">
                                Home
                            </a>
                            <a href="#" class="headerNav__item hoverColorPrimary" aria-label="Go to Videos" title="Go to Videos">
                                Videos
                            </a>
                            <a href="#" class="headerNav__item hoverColorPrimary" aria-label="Go to Channels" title="Go to Channels">
                                Channels
                            </a>
                        </nav>   

                        <ul class="headerSubitens">
                            <li class="headerSubitens__item">
                                <a href="#" aria-label="Go to Subscription" title="Go to Subscription">Subscription</a>
                            </li>
                            <li class="headerSubitens__item">
                                <a href="#" aria-label="Go to History" title="Go to History">History</a>
                            </li>
                            <li class="headerSubitens__item">
                                <a href="#" aria-label="Go to Upload" title="Go to Upload">Upload</a>
                            </li>
                        </ul>                
                    </div>
                </div>

                <div class="d-md-none flex-fill text-end">
                    <a 
                        class="colorPrimary"
                        href="javascript:void()"
                        aria-label="Open menu"
                        title="Open menu"
                    >
                        <span class="material-icons">more_vert</span>
                    </a>
                </div>
            </div>

        </div>
    </header>
</template>

<style src="./Header.scss" lang="scss" scoped />
