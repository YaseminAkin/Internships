<template>
  <body class="__className_20951f">
    <div class="bg-gray-100 dark:bg-blueish-light flex flex-col min-h-screen">
      <Navbar />
      <article class="p-2 m-2 format lg:format-lg dark:format-invert mx-auto">
        <div>
          <center><h2 id="terms-and-conditions">Terms and Conditions</h2></center>

          <h3 id="platform-registration-and-usage">Platform Registration and Usage</h3>
          <p>
            To access and use this platform, you must register using one of your social media
            accounts, such as Google, Facebook, or Twitter. Upon registration, you also agree to
            subscribe to our newsletter. The platform offers different plans, including a free
            "Starter" tier and paid plans like "Pro" and "Agency." Access to specific features on
            the platform is subject to the plan you select and these terms and conditions.
          </p>

          <h3 id="accuracy-of-information">Accuracy of Information</h3>
          <p>
            The platform generates information using GPT-3.5 and GPT-4 technology for general
            informational purposes only. Neither the website nor its affiliates represent or endorse
            the accuracy or reliability of this information. No representation or warranty of any
            kind, express or implied, is made regarding the completeness, accuracy, reliability,
            suitability, or availability of the information generated by GPT-3.5 and GPT-4
            technology. You assume full responsibility for any reliance on such information.
          </p>

          <h3 id="payment-processing">Payment Processing</h3>
          <p>
            We employ Stripe, a third-party payment processor, to handle transactions for our paid
            plans. We do not store your financial information on our servers. By choosing a paid
            plan, you consent to share your payment information with Stripe and agree to their terms
            of service and privacy policy.
          </p>

          <h3 id="disclaimer-of-warranties">Disclaimer of Warranties</h3>
          <p>
            The Service is supplied on an "AS IS", inclusive of all faults and defects, without any
            guarantees. VenturusAI, within the bounds of the law, renounces all forms of warranties,
            whether express, implied, statutory, or otherwise, such as warranties of
            merchantability, suitability for a specific purpose, title, and non-infringement.
            VenturusAI does not guarantee or promise, nor does it claim that the Service will
            satisfy your needs, deliver desired outcomes, be compatible with other software,
            applications, systems, or services, function without disruptions, adhere to performance
            or dependability criteria, or be devoid of errors.
          </p>

          <h3 id="prohibited-content">Prohibited Content</h3>
          <p>
            You may not transmit any content that is unlawful, offensive, upsetting, intended to
            disgust, threatening, libelous, defamatory, obscene, or otherwise objectionable.
            Examples include but are not limited to:
          </p>
          <ul>
            <li>Unlawful or promoting unlawful activity.</li>
            <li>
              Defamatory, discriminatory, or mean-spirited content targeting religion, race, sexual
              orientation, gender, national/ethnic origin, or other groups.
            </li>
            <li>
              Spam, unauthorized or unsolicited advertising, chain letters, gambling, or lottery
              content.
            </li>
            <li>
              Content containing viruses, malware, or designed to disrupt, damage, or limit the
              functioning of software, hardware, or telecommunications equipment or to obtain
              unauthorized access to third-party data.
            </li>
            <li>
              Infringement of any party's proprietary rights, including patents, trademarks, trade
              secrets, copyrights, or publicity rights.
            </li>
          </ul>
          <p>Violations may result in immediate account termination without notice.</p>

          <h3 id="your-information-order-cancellation-and-refunds">
            Your Information, Order Cancellation and Refunds
          </h3>

          <h4 id="your-information">Your Information</h4>
          <p>
            When purchasing a subscription plan or an advanced report, you may be asked to provide
            information relevant to your order, including your name and email. You represent and
            warrant that (i) you have the legal right to use any credit or debit card(s) or other
            payment method(s) in connection with any order; and (ii) the information you supply to
            us is true, correct, and complete. By submitting this information, you grant us the
            right to provide it to third-party payment processors for the purpose of facilitating
            your order.
          </p>

          <h4 id="order-cancellation-by-venturusai">Order Cancellation by VenturusAI</h4>
          <p>
            We reserve the right to refuse or cancel your order at any time for reasons including,
            but not limited to:
          </p>
          <ul>
            <li>Advanced Report availability</li>
            <li>Infrastructural issues or limitations</li>
            <li>Errors with your order</li>
            <li>
              We may also refuse or cancel your order if fraud or an unauthorized or illegal
              transaction is suspected.
            </li>
          </ul>

          <h4 id="subscription-cancellation-by-customer">Subscription Cancellation by Customer</h4>
          <p>
            You may cancel your subscription at any time. To cancel, you must follow the
            cancellation process provided on our platform or contact our customer support. Once your
            subscription is canceled, you will lose access to the features and benefits associated
            with your paid plan. Please note that canceling your subscription will not result in a
            refund for any unused portion of your subscription period.
          </p>

          <h4 id="refunds">Refunds</h4>
          <p>
            <strong
              ><em
                >Due to the custom nature of the reports generated by our platform, once an order
                has been placed and the report has been generated, you will not have the right to
                cancel the order or request a refund.</em
              ></strong
            >
            Please ensure that you carefully review your order before submitting it.
          </p>

          <h3 id="limitation-of-liability">Limitation of Liability</h3>
          <p>
            The website and its affiliates will not be liable for any losses or damages arising from
            the use of this platform or the information provided through it. Users are responsible
            for the content they create and transmit using the platform. In no event shall
            VenturusAI, its affiliates, or their respective licensors and service providers, be
            liable for any consequential, incidental, direct, indirect, special, punitive, or other
            damages, including but not limited to, loss of production, loss of profit, loss of
            revenue, loss of use, loss of goodwill, loss of data, or other losses, whether based in
            contract, tort (including negligence), strict liability, or otherwise, arising from your
            use of the platform or reliance on any information provided through it, even if
            VenturusAI or any of its affiliates have been advised of the possibility of such
            damages.
          </p>

          <p>
            The information provided by this website is generated using GPT-3.5 and GPT-4 technology
            and is for general informational purposes only. The website and VenturusAI team are not
            affiliated with OpenAI and do not represent or endorse its accuracy or reliability. The
            information provided may contain errors or inaccuracies and is not intended as business
            advice. The website and its affiliates will not be liable for any losses or damages
            arising from the use of this information.
          </p>
        </div>
      </article>
      <FooterP />
    </div>
  </body>
</template>

<script>
import Navbar from '../myComponents/navbar.vue'
import FooterP from '../myComponents/footer.vue'

export default {
  components: {
    Navbar,
    FooterP
  },
  name: 'Terms-P',
  mounted() {
    document.title = 'Terms and conditions - VenturusAI'
  }
}
</script>
