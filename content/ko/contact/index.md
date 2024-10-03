---
title: Contact
date: 2024-10-04

type: landing

sections:
  - block: contact
    content:
      title: Contact Us
      text: |-
        If you have any inquiries, please feel free to contact us using the form below or reach out through the provided contact details.
      email: info@example.com
      phone: +1 234 567 8900
      address:
        street: 123 Example Street
        city: New York
        region: NY
        postcode: '10001'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.712776'
        longitude: '-74.005974'
      directions: |-
        We are located in downtown New York, easily accessible by subway and bus.
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        netlify:
          success_url: /thanks/ # 폼 제출 성공 후 리다이렉트할 페이지
          captcha: true          # CAPTCHA 사용 여부 설정
        attachments: true         # 파일 첨부 활성화 여부

    design:
      columns: '2'
---
