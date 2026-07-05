<table width="100%" cellpadding="0" cellspacing="0" style="font-family: Arial, sans-serif; background-color: #f5f5f5;">
  <tr>
    <td align="center" style="padding: 20px;">
      <table width="600" cellpadding="0" cellspacing="0" style="background-color: white; border-collapse: collapse;">
        
        <!-- HEADER -->
        <tr>
          <td style="background-color: #667eea; color: white; padding: 40px 20px; text-align: center;">
            <h1 style="margin: 0 0 10px 0; font-size: 28px; font-weight: 600;">🎉 Welcome Aboard!</h1>
            <p style="margin: 0; font-size: 16px; color: #ffffff;">Your journey starts here</p>
          </td>
        </tr>

        <!-- CONTENT -->
        <tr>
          <td style="padding: 40px; color: #333;">
            
            <!-- GREETING -->
            <p style="font-size: 18px; margin: 0 0 20px 0; line-height: 1.6;">
              Hello <strong style="color: #667eea;">{$json.firstName} {$json.lastName}</strong>,
              <br><br>
              We're absolutely thrilled to have you join our platform! 🚀 Get ready to experience innovation at its finest.
            </p>

            <!-- ACCOUNT DETAILS SECTION -->
            <h3 style="font-size: 16px; font-weight: 600; color: #667eea; margin: 30px 0 15px 0; text-transform: uppercase; letter-spacing: 1px;">Your Account Details</h3>
            <table width="100%" cellpadding="0" cellspacing="0" style="background-color: #f8f9fa; border-left: 4px solid #667eea; margin-bottom: 20px;">
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Username</strong><br>
                  {$json.username}
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Email</strong><br>
                  {$json.email}
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; font-size: 14px;">
                  <strong style="color: #555;">Phone</strong><br>
                  {$json.phone}
                </td>
              </tr>
            </table>

            <!-- PROFILE INFORMATION SECTION -->
            <h3 style="font-size: 16px; font-weight: 600; color: #667eea; margin: 30px 0 15px 0; text-transform: uppercase; letter-spacing: 1px;">Profile Information</h3>
            <table width="100%" cellpadding="0" cellspacing="0" style="background-color: #f8f9fa; border-left: 4px solid #667eea; margin-bottom: 20px;">
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Full Name</strong><br>
                  {$json.firstName} {$json.lastName}
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Age</strong><br>
                  {$json.age} years
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Location</strong><br>
                  {$json.address.city}, {$json.address.state}
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; border-bottom: 1px solid #e0e0e0; font-size: 14px;">
                  <strong style="color: #555;">Company</strong><br>
                  {$json.company.name}
                </td>
              </tr>
              <tr>
                <td style="padding: 12px 15px; font-size: 14px;">
                  <strong style="color: #555;">Position</strong><br>
                  {$json.company.title}
                </td>
              </tr>
            </table>

            <!-- DIVIDER -->
            <hr style="border: none; border-top: 1px solid #e0e0e0; margin: 30px 0;">

            <!-- GETTING STARTED SECTION -->
            <h3 style="font-size: 16px; font-weight: 600; color: #667eea; margin: 30px 0 15px 0; text-transform: uppercase; letter-spacing: 1px;">Get Started in 4 Simple Steps</h3>
            <table width="100%" cellpadding="0" cellspacing="0" style="background-color: #f8f9fa; margin-bottom: 20px;">
              <tr>
                <td style="padding: 15px;">
                  <table width="100%" cellpadding="0" cellspacing="0">
                    <tr>
                      <td style="width: 40px; text-align: center;">
                        <div style="background-color: #667eea; color: white; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-weight: 600; font-size: 14px;">1</div>
                      </td>
                      <td style="padding-left: 15px; font-size: 14px; padding-bottom: 15px; border-bottom: 1px solid #e0e0e0;">
                        <strong>Log In</strong> - Use your username and password to access your account
                      </td>
                    </tr>
                  </table>
                  <table width="100%" cellpadding="0" cellspacing="0" style="margin-top: 15px;">
                    <tr>
                      <td style="width: 40px; text-align: center;">
                        <div style="background-color: #667eea; color: white; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-weight: 600; font-size: 14px;">2</div>
                      </td>
                      <td style="padding-left: 15px; font-size: 14px; padding-bottom: 15px; border-bottom: 1px solid #e0e0e0;">
                        <strong>Complete Your Profile</strong> - Add a profile picture and update your preferences
                      </td>
                    </tr>
                  </table>
                  <table width="100%" cellpadding="0" cellspacing="0" style="margin-top: 15px;">
                    <tr>
                      <td style="width: 40px; text-align: center;">
                        <div style="background-color: #667eea; color: white; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-weight: 600; font-size: 14px;">3</div>
                      </td>
                      <td style="padding-left: 15px; font-size: 14px; padding-bottom: 15px; border-bottom: 1px solid #e0e0e0;">
                        <strong>Enable Security</strong> - Set up two-factor authentication for enhanced protection
                      </td>
                    </tr>
                  </table>
                  <table width="100%" cellpadding="0" cellspacing="0" style="margin-top: 15px;">
                    <tr>
                      <td style="width: 40px; text-align: center;">
                        <div style="background-color: #667eea; color: white; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-weight: 600; font-size: 14px;">4</div>
                      </td>
                      <td style="padding-left: 15px; font-size: 14px;">
                        <strong>Explore Features</strong> - Discover all the amazing features we have to offer
                      </td>
                    </tr>
                  </table>
                </td>
              </tr>
            </table>

            <!-- CTA BUTTON -->
            <div style="text-align: center; margin: 30px 0;">
              <a href="https://platform.example.com/login" style="background-color: #667eea; color: white; padding: 12px 30px; text-decoration: none; border-radius: 5px; font-weight: 600; display: inline-block;">
                Get Started Now →
              </a>
            </div>

            <!-- SUPPORT SECTION -->
            <table width="100%" cellpadding="0" cellspacing="0" style="background-color: #e8f4f8; border-left: 4px solid #17a2b8; margin-bottom: 20px;">
              <tr>
                <td style="padding: 15px;">
                  <p style="font-size: 14px; color: #333; margin: 0 0 10px 0;">
                    <strong>Need Help?</strong> Our friendly support team is here 24/7 to assist you with any questions or concerns.
                  </p>
                  <p style="font-size: 13px; color: #666; margin: 0;">
                    Just <a href="mailto:support@platform.com" style="color: #17a2b8; text-decoration: none;">reply to this email</a> or <a href="https://platform.example.com/support" style="color: #17a2b8; text-decoration: none;">contact our support team</a>
                  </p>
                </td>
              </tr>
            </table>

          </td>
        </tr>

        <!-- FOOTER -->
        <tr>
          <td style="background-color: #f8f9fa; padding: 30px 40px; text-align: center; font-size: 13px; color: #666; border-top: 1px solid #e0e0e0;">
            <p style="margin: 0 0 15px 0; font-weight: 600;">Welcome to Our Community!</p>
            <p style="margin: 0 0 15px 0; line-height: 1.6;">
              We're excited to have you on board. If you have any questions, feedback, or suggestions, don't hesitate to reach out.
            </p>
            <p style="margin: 0 0 20px 0; font-size: 12px;">
              <a href="https://platform.example.com/about" style="color: #667eea; text-decoration: none; margin: 0 10px;">About Us</a>
              <a href="https://platform.example.com/privacy" style="color: #667eea; text-decoration: none; margin: 0 10px;">Privacy Policy</a>
              <a href="https://platform.example.com/terms" style="color: #667eea; text-decoration: none; margin: 0 10px;">Terms of Service</a>
            </p>
            <p style="margin: 0; font-size: 11px; color: #999;">
              © 2024 Our Platform. All rights reserved.
            </p>
          </td>
        </tr>

      </table>
    </td>
  </tr>
</table>