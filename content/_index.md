---
title: 'Home'
date: 2025-09-13
type: landing

design:
  # Default section spacing
  spacing: '1rem'

sections:
  - block: hero
    content:
      title: Mario's Unisex Barber
      text: Proudly cutting hair in New Milford, NJ since 2018
      primary_action:
        text: Book Now
        url: https://hugoblox.com/templates/
        icon: calendar
      secondary_action:
        text: Menu
        url: /#menu
      announcement:
        text:
        link:
          text:
          url:
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: 'dark'
      background:
        color: 'navy'
        image:
          # Add your image background to `assets/media/`.
          filename: marios_barber_shop_interior.jpg
          filters:
            brightness: 0.3
  - block: stats
    content:
      items:
        - statistic: '25+'
          description: |
            years of experience
        - statistic: '50+'
          description: |
            5-star reviews on Google
        - statistic: '8 years'
          description: |
            in New Milford, NJ
    design:
      # Section background color (CSS class)
      css_class: 'bg-gray-100 dark:bg-gray-900'
      # Reduce spacing
      spacing:
        padding: ['1rem', 0, '1rem', 0]
  - block: features
    id: menu
    content:
      title: Menu
      text: We serve children and adults of any age
      items:
        - name: <center>Haircuts</center>
          icon: scissors
          description: |
            <br>
            <p>Kid's Cut: <span style="float: right;"><b>$20</b></span></p>
            <p>&nbsp</p>
            <p>Adult's Cut: <span style="float: right;"><b>$25</b></span></p>
            <p>&nbsp</p>
            <p>Senior's Cut: <span style="float: right;"><b>$20</b></span></p>
        - name: <center>Color & Styling</center>
          icon: paint-brush
          description: |
            <br>
            <p>Color: <span style="float: right;"><b>$45+</b></span></p>
            <p>&nbsp</p>
            <p>Blowout (Medium): <span style="float: right;"><b>$30</b></span></p>
            <p>Blowout (Long): <span style="float: right;"><b>$45+</b></span></p>
            <p>&nbsp</p>
            <p>Deep Condition: <span style="float: right;"><b>$20</b></span></p>
            <p>&nbsp</p>
            <p>Keratin: <span style="float: right;"><b>$150</b></span></p>
        - name: <center>Beard</center>
          icon: face-smile
          description: |
            <br>
            <p>Beard Trim: <span style="float: right;"><b>$10</b></span></p>
            <p>&nbsp</p>
            <p>Beard Shave: <span style="float: right;"><b>$10</b></span></p>
            <p>&nbsp</p>
            <p>Beard Shampoo: <span style="float: right;"><b>$5</b></span></p>
  - block: markdown
    id: gallery
    content:
      title: Photo Gallery
      text: |
        <div class="gallery-container" style="display: flex; overflow-x: auto; gap: 1rem; padding: 1rem 0; scroll-behavior: smooth;">
          <div class="gallery-item" style="flex: 0 0 auto; width: 300px; text-align: center;">
            <img src="/assets/media/marios_barber_shop_interior.jpg" alt="Barber Shop Interior" style="width: 100%; height: 200px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p style="margin-top: 0.5rem; font-size: 0.9rem; color: #666;">Barber Shop Interior</p>
          </div>
          <div class="gallery-item" style="flex: 0 0 auto; width: 300px; text-align: center;">
            <img src="/assets/media/coffee.jpg" alt="Coffee Break" style="width: 100%; height: 200px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p style="margin-top: 0.5rem; font-size: 0.9rem; color: #666;">Coffee Break</p>
          </div>
          <div class="gallery-item" style="flex: 0 0 auto; width: 300px; text-align: center;">
            <img src="/assets/media/testimonial-1.jpg" alt="Customer Testimonial" style="width: 100%; height: 200px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
            <p style="margin-top: 0.5rem; font-size: 0.9rem; color: #666;">Customer Testimonial</p>
          </div>
        </div>
    design:
      columns: '1'
      css_class: 'bg-gray-50 dark:bg-gray-800'
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - 'Dedicated support channel'
            - '3,000+ users on Discord'
            - 'Share your site and get feedback'
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: 'bg-gray-100 dark:bg-gray-900'
  - block: testimonials
    content:
      title: ''
      text: ''
      items:
        - name: 'Hugo Smith'
          role: 'Marketing Executive at X'
          # Upload image to `assets/media/` and reference the filename here
          image: 'testimonial-1.jpg'
          text: 'Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!'
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ['6rem', 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Book Now
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-700'
        css_style: ''
---
