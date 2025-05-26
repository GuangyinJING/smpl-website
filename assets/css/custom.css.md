/* Justify text in the hero section */
.hero-content .hero-text {
  text-align: justify;
}

/* Shift welcome.jpg left and downward */
.hero-content .hero-image {
  transform: translate(-40px, 40px); /* 40px right, 40px down */
}

.page-header .banner {
  max-height: 800px; /* Limit banner height */
  overflow: hidden; /* Crop excess */
}
.page-header .banner img {
  width: 100%; /* Fit width */
  height: auto; /* Maintain aspect ratio */
  object-fit: cover; /* Crop to fit */
  object-position: center; /* Center image */
}

/* Adjust banner height for Contact page */
.page-header .banner {
  max-height: 800px; /* Match image height */
  overflow: hidden; /* Prevent overflow */
}
.page-header .banner img {
  width: 100%; /* Fit container width */
  height: 800px; /* Set exact height */
  object-fit: contain; /* Display full image without cropping */
  object-position: center; /* Center image */
}