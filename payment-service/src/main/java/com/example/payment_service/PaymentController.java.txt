package com.example.paymentservice;

import org.springframework.web.bind.annotation.*;

@RestController
@RequestMapping("/payments")
public class PaymentController {

    @GetMapping
    public String getPayments() {
        return "Payment Service Running!";
    }
}